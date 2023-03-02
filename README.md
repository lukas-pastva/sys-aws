# sys-aws

- CloudFormation for creating ec2

```
aws cloudformation create-stack --stack-name CreateEC2 --template-body cf-ec2.yml

aws cloudformation describe-stacks --stack-name CreateEC2

aws cloudformation delete-stack --stack-name CreateEC2         
```
