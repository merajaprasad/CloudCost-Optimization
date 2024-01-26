# Cloud Cost Optimization
created a Lambda function that identifies EBS snapshots which is not associated with any running EC2 instance and deletes those snapshots to save on cloud costs.
## Steps Need to Follow
Create EC2 Instances
Take snapshot of EBS volume
Create Lambda Function
Paste The python script and save
Increase the execution time to 10 sec
Create a IAM Policy
  choose below permission to create
    1. describe snapshot
    2. delete snapshot
    3. describe volume
    4. descrive instances
Attach the policy to Lambda Execution Role
run/test the lambda code
