# AWS-IAM
AWS, Identify Access Management
IAM link: https://docs.aws.amazon.com/IAM/latest/UserGuide/introduction.html \
Root user \
User \
Group \
Role \
User & Password vs Access Key ID  \ & Secret Key. \
Policy, deny vs allow, deny overrides allow in the same permission. \
Password policy \
Minium permission principle \
IAM user vs Federated user 

Best Practice of IAM: \
1 Don't use IAM to do the regular work. \
2 MFA, multi-factor authentication. \
3 IAM is HA solution in global, but with the low latency.
Don't inlcude IAM changes in the critical, high-availability code paths of your application. Instead, make IAM changes in a separate initialization or setup routine that you run less frequently. \
4 The same perssmion, deny override allow. \
5 Federated user(Non-IAM user) with IAM, for exmaple Windows SSO with IAM.
