- 3 x private subnets in default vpc
- 1 x private NAT Gateway in default vpc
- 1 x Inbound rule in default Security Group

Run vpc.yaml on aws cloudformation
- [vpc.yaml](./vpc.yaml)

aws cloudformation create-stack --stack-name vpc --template-body file://vpc.yaml