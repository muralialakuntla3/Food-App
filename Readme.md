# Cloud Formation - IaC

## Templates: 
CloudFormation uses templates written in JSON or YAML format to describe the desired AWS resources and their configurations. These templates define the structure of your infrastructure.
## Stacks: 
A stack is a collection of AWS resources created and managed as a single unit. You create a stack by providing a CloudFormation template, and CloudFormation handles the creation, updating, and deletion of the resources defined in the template.

## create template for ec2 setup and app deployment
## create cloud formation stack
   ### Goto aws cloud
   ### Goto services section and choose CloudFormation
   ### Left side choose Stack
   ### Create stack
        Step-1 : create stack
        Step-2 : specify stack details
        Step-3 : configure stack options
        Step-4 : review & create

## Don’t forget to delete things
    Stack : -> CloudFormation -> stack -> delete
    S3 bucket: -> S3 buckets -> empty bucket -> delete bucket
