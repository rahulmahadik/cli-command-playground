# AWS CLI Commands Cheatsheet

> AWS CLI is the official command-line interface for Amazon Web Services. Manage cloud resources from terminal.

## Quick Reference

> **Preview** — This is a curated selection of key commands. Explore the full command list with examples, practice exercises, and more on [Command Playground](https://technoscripts.com/command-playground/?utm_source=github&utm_medium=repository&utm_campaign=explore-all).

| Command | Description |
|---------|-------------|
| `aws configure` | Set up AWS CLI credentials |
| `aws configure list` | List current configuration settings |
| `aws configure list-profiles` | List all configured profiles |
| `aws configure get` | Get a specific config value |
| `aws configure set` | Set a specific config value |
| `aws sts get-caller-identity` | Show the current IAM identity |
| `aws sts assume-role` | Assume an IAM role temporarily |
| `aws sts get-session-token` | Get temporary security credentials |
| `aws ec2 describe-instances` | List all EC2 instances |
| `aws ec2 run-instances` | Launch new EC2 instances |
| `aws ec2 start-instances` | Start stopped EC2 instances |
| `aws ec2 stop-instances` | Stop running EC2 instances |
| `aws ec2 terminate-instances` | Terminate EC2 instances permanently |
| `aws ec2 reboot-instances` | Reboot running EC2 instances |
| `aws ec2 describe-security-groups` | List security groups |
| `aws ec2 create-security-group` | Create a new security group |
| `aws ec2 authorize-security-group-ingress` | Add inbound security group rule |
| `aws ec2 describe-key-pairs` | List SSH key pairs |
| `aws ec2 create-key-pair` | Create a new SSH key pair |
| `aws ec2 describe-vpcs` | List all VPCs |
| `aws ec2 describe-subnets` | List all subnets |
| `aws ec2 describe-images` | List available AMI images |
| `aws ec2 create-image` | Create an AMI from an instance |
| `aws ec2 describe-volumes` | List EBS volumes |
| `aws ec2 create-volume` | Create a new EBS volume |
| `aws ec2 attach-volume` | Attach an EBS volume to an instance |
| `aws ec2 describe-snapshots` | List EBS snapshots |
| `aws ec2 create-snapshot` | Create an EBS volume snapshot |
| `aws ec2 allocate-address` | Allocate an Elastic IP address |
| `aws ec2 associate-address` | Associate an Elastic IP to an instance |
| `aws ec2 describe-addresses` | List Elastic IP addresses |
| `aws ec2 create-tags` | Add tags to AWS resources |
| `aws ec2 describe-tags` | List tags on AWS resources |
| `aws s3 ls` | List S3 buckets or objects |
| `aws s3 cp` | Copy files to/from S3 |
| `aws s3 mv` | Move files to/from S3 |
| `aws s3 rm` | Delete S3 objects |
| `aws s3 sync` | Sync local directory with S3 |
| `aws s3 mb` | Create a new S3 bucket |
| `aws s3 rb` | Remove an S3 bucket |
| `aws s3 presign` | Generate a pre-signed S3 URL |
| `aws s3api list-buckets` | List all S3 buckets via API |
| `aws s3api create-bucket` | Create an S3 bucket via API |
| `aws s3api delete-bucket` | Delete an S3 bucket via API |
| `aws s3api put-object` | Upload an object to S3 |
| `aws s3api get-object` | Download an object from S3 |
| `aws s3api list-objects-v2` | List objects in an S3 bucket |
| `aws s3api put-bucket-policy` | Set a bucket policy |
| `aws s3api get-bucket-policy` | Get a bucket policy |
| `aws s3api put-bucket-versioning` | Enable bucket versioning |
| `aws s3api put-public-access-block` | Block public access to a bucket |
| `aws s3api head-object` | Get object metadata |
| `aws s3api copy-object` | Copy an object within S3 |
| `aws iam list-users` | List all IAM users |
| `aws iam create-user` | Create a new IAM user |
| `aws iam delete-user` | Delete an IAM user |
| `aws iam get-user` | Get IAM user details |
| `aws iam list-roles` | List all IAM roles |
| `aws iam create-role` | Create a new IAM role |
| `aws iam delete-role` | Delete an IAM role |
| `aws iam attach-role-policy` | Attach a policy to a role |
| `aws iam detach-role-policy` | Detach a policy from a role |
| `aws iam list-policies` | List all IAM policies |
| `aws iam create-policy` | Create a new IAM policy |
| `aws iam get-policy` | Get IAM policy details |
| `aws iam list-attached-role-policies` | List policies attached to a role |
| `aws iam list-groups` | List all IAM groups |
| `aws iam create-group` | Create a new IAM group |
| `aws iam add-user-to-group` | Add a user to a group |
| `aws iam create-access-key` | Create an access key for a user |
| `aws iam list-access-keys` | List access keys for a user |
| `aws iam delete-access-key` | Delete an access key |
| `aws iam attach-user-policy` | Attach a policy to a user |
| `aws iam list-instance-profiles` | List instance profiles |
| `aws iam create-instance-profile` | Create an instance profile |
| `aws lambda list-functions` | List all Lambda functions |
| `aws lambda create-function` | Create a new Lambda function |
| `aws lambda delete-function` | Delete a Lambda function |
| `aws lambda invoke` | Invoke a Lambda function |
| `aws lambda update-function-code` | Update Lambda function code |
| `aws lambda update-function-configuration` | Update Lambda function config |
| `aws lambda get-function` | Get Lambda function details |
| `aws lambda publish-version` | Publish a Lambda function version |
| `aws lambda create-alias` | Create a Lambda function alias |
| `aws lambda list-aliases` | List Lambda function aliases |
| `aws lambda list-layers` | List Lambda layers |
| `aws lambda publish-layer-version` | Publish a new Lambda layer version |
| `aws lambda add-permission` | Add a permission to a Lambda function |
| `aws lambda get-policy` | Get Lambda function resource policy |
| `aws lambda list-event-source-mappings` | List event source mappings |
| `aws lambda create-event-source-mapping` | Create an event source mapping |
| `aws rds describe-db-instances` | List all RDS instances |
| `aws rds create-db-instance` | Create a new RDS instance |
| `aws rds delete-db-instance` | Delete an RDS instance |
| `aws rds start-db-instance` | Start a stopped RDS instance |
| `aws rds stop-db-instance` | Stop a running RDS instance |
| `aws rds reboot-db-instance` | Reboot an RDS instance |
| `aws rds modify-db-instance` | Modify RDS instance settings |
| `aws rds describe-db-snapshots` | List RDS snapshots |
| `aws rds create-db-snapshot` | Create an RDS snapshot |
| `aws rds restore-db-instance-from-db-snapshot` | Restore RDS from a snapshot |
| `aws rds describe-db-clusters` | List Aurora DB clusters |
| `aws rds create-db-cluster` | Create an Aurora DB cluster |
| `aws rds describe-db-subnet-groups` | List DB subnet groups |
| `aws rds create-db-subnet-group` | Create a DB subnet group |
| `aws rds describe-db-parameter-groups` | List DB parameter groups |
| `aws dynamodb list-tables` | List all DynamoDB tables |
| `aws dynamodb create-table` | Create a new DynamoDB table |
| `aws dynamodb delete-table` | Delete a DynamoDB table |
| `aws dynamodb describe-table` | Get DynamoDB table details |
| `aws dynamodb put-item` | Insert an item into a table |
| `aws dynamodb get-item` | Get an item from a table |
| `aws dynamodb update-item` | Update an item in a table |
| `aws dynamodb delete-item` | Delete an item from a table |
| `aws dynamodb query` | Query items by key conditions |
| `aws dynamodb scan` | Scan all items in a table |
| `aws dynamodb batch-write-item` | Write multiple items in batch |
| `aws dynamodb batch-get-item` | Get multiple items in batch |
| `aws dynamodb update-table` | Update DynamoDB table settings |
| `aws dynamodb describe-time-to-live` | Get TTL settings for a table |
| `aws dynamodb update-time-to-live` | Set TTL for a table |
| `aws cloudformation list-stacks` | List all CloudFormation stacks |
| `aws cloudformation create-stack` | Create a new CloudFormation stack |
| `aws cloudformation update-stack` | Update an existing stack |
| `aws cloudformation delete-stack` | Delete a CloudFormation stack |
| `aws cloudformation describe-stacks` | Describe CloudFormation stacks |
| `aws cloudformation describe-stack-events` | List stack events |
| `aws cloudformation describe-stack-resources` | List stack resources |
| `aws cloudformation validate-template` | Validate a CloudFormation template |
| `aws cloudformation get-template` | Get the stack template body |
| `aws cloudformation create-change-set` | Create a change set for a stack |
| `aws cloudformation execute-change-set` | Execute a change set |
| `aws cloudformation list-exports` | List all stack exports |
| `aws cloudformation deploy` | Deploy a CloudFormation template |
| `aws cloudformation package` | Package local artifacts for deployment |
| `aws ecs list-clusters` | List all ECS clusters |
| `aws ecs create-cluster` | Create a new ECS cluster |
| `aws ecs delete-cluster` | Delete an ECS cluster |
| `aws ecs describe-clusters` | Describe ECS clusters |
| `aws ecs list-services` | List ECS services in a cluster |
| `aws ecs create-service` | Create a new ECS service |
| `aws ecs update-service` | Update an ECS service |
| `aws ecs delete-service` | Delete an ECS service |
| `aws ecs describe-services` | Describe ECS services |
| `aws ecs list-tasks` | List ECS tasks |
| `aws ecs run-task` | Run a new ECS task |
| `aws ecs stop-task` | Stop a running ECS task |
| `aws ecs describe-tasks` | Describe ECS tasks |
| `aws ecs list-task-definitions` | List ECS task definitions |
| `aws ecs register-task-definition` | Register a new task definition |
| `aws ecs deregister-task-definition` | Deregister a task definition |
| `aws ecs describe-task-definition` | Describe a task definition |
| `aws ecs execute-command` | Run a command in an ECS container |
| `aws eks list-clusters` | List all EKS clusters |
| `aws eks create-cluster` | Create a new EKS cluster |
| `aws eks delete-cluster` | Delete an EKS cluster |
| `aws eks describe-cluster` | Describe an EKS cluster |
| `aws eks update-kubeconfig` | Update kubeconfig for an EKS cluster |
| `aws eks list-nodegroups` | List EKS node groups |
| `aws eks create-nodegroup` | Create an EKS node group |
| `aws eks delete-nodegroup` | Delete an EKS node group |
| `aws eks describe-nodegroup` | Describe an EKS node group |
| `aws eks list-fargate-profiles` | List EKS Fargate profiles |
| `aws eks create-fargate-profile` | Create an EKS Fargate profile |
| `aws eks list-addons` | List EKS cluster add-ons |
| `aws eks create-addon` | Install an EKS add-on |
| `aws logs describe-log-groups` | List CloudWatch log groups |
| `aws logs create-log-group` | Create a CloudWatch log group |
| `aws logs delete-log-group` | Delete a CloudWatch log group |
| `aws logs describe-log-streams` | List log streams in a group |
| `aws logs get-log-events` | Get log events from a stream |
| `aws logs filter-log-events` | Filter log events by pattern |
| `aws logs tail` | Tail CloudWatch logs in real time |
| `aws logs put-log-events` | Put log events into a stream |
| `aws cloudwatch list-metrics` | List available CloudWatch metrics |
| `aws cloudwatch get-metric-statistics` | Get CloudWatch metric statistics |
| `aws cloudwatch put-metric-data` | Publish custom metric data |
| `aws cloudwatch describe-alarms` | List CloudWatch alarms |
| `aws cloudwatch put-metric-alarm` | Create a CloudWatch alarm |
| `aws cloudwatch delete-alarms` | Delete CloudWatch alarms |
| `aws cloudwatch set-alarm-state` | Set CloudWatch alarm state manually |
| `aws cloudwatch list-dashboards` | List CloudWatch dashboards |
| `aws ec2 create-vpc` | Create a new VPC |
| `aws ec2 delete-vpc` | Delete a VPC |
| `aws ec2 create-subnet` | Create a subnet in a VPC |
| `aws ec2 delete-subnet` | Delete a subnet |
| `aws ec2 create-internet-gateway` | Create an internet gateway |
| `aws ec2 attach-internet-gateway` | Attach an internet gateway to a VPC |
| `aws ec2 create-nat-gateway` | Create a NAT gateway |
| `aws ec2 describe-nat-gateways` | List NAT gateways |
| `aws ec2 create-route-table` | Create a route table |
| `aws ec2 create-route` | Add a route to a route table |
| `aws ec2 associate-route-table` | Associate a route table with a subnet |
| `aws ec2 describe-route-tables` | List route tables |
| `aws ec2 describe-internet-gateways` | List internet gateways |
| `aws ec2 create-network-acl` | Create a network ACL |
| `aws ec2 describe-network-acls` | List network ACLs |
| `aws ec2 create-vpc-endpoint` | Create a VPC endpoint |
| `aws ec2 describe-vpc-endpoints` | List VPC endpoints |
| `aws route53 list-hosted-zones` | List all Route 53 hosted zones |
| `aws route53 create-hosted-zone` | Create a Route 53 hosted zone |
| `aws route53 delete-hosted-zone` | Delete a Route 53 hosted zone |
| `aws route53 get-hosted-zone` | Get hosted zone details |
| `aws route53 list-resource-record-sets` | List DNS records in a zone |
| `aws route53 change-resource-record-sets` | Create or update DNS records |
| `aws route53 list-health-checks` | List Route 53 health checks |
| `aws route53 create-health-check` | Create a health check |
| `aws route53domains list-domains` | List registered domains |
| `aws route53domains get-domain-detail` | Get domain registration details |
| `aws elbv2 describe-load-balancers` | List all load balancers |
| `aws elbv2 create-load-balancer` | Create a new load balancer |
| `aws elbv2 delete-load-balancer` | Delete a load balancer |
| `aws elbv2 describe-target-groups` | List target groups |
| `aws elbv2 create-target-group` | Create a target group |
| `aws elbv2 delete-target-group` | Delete a target group |
| `aws elbv2 register-targets` | Register targets with a group |
| `aws elbv2 deregister-targets` | Deregister targets from a group |
| `aws elbv2 describe-target-health` | Check target health status |
| `aws elbv2 describe-listeners` | List load balancer listeners |
| `aws elbv2 create-listener` | Create a load balancer listener |
| `aws elbv2 describe-rules` | List listener rules |
| `aws elbv2 create-rule` | Create a listener rule |
| `aws elb describe-load-balancers` | List Classic load balancers |
| `aws sns list-topics` | List all SNS topics |
| `aws sns create-topic` | Create an SNS topic |
| `aws sns delete-topic` | Delete an SNS topic |
| `aws sns publish` | Publish a message to an SNS topic |
| `aws sns subscribe` | Subscribe to an SNS topic |
| `aws sns unsubscribe` | Unsubscribe from an SNS topic |
| `aws sns list-subscriptions` | List all SNS subscriptions |
| `aws sqs list-queues` | List all SQS queues |
| `aws sqs create-queue` | Create an SQS queue |
| `aws sqs delete-queue` | Delete an SQS queue |
| `aws sqs send-message` | Send a message to an SQS queue |
| `aws sqs receive-message` | Receive messages from an SQS queue |
| `aws sqs delete-message` | Delete a message from an SQS queue |
| `aws sqs get-queue-attributes` | Get SQS queue attributes |
| `aws sqs purge-queue` | Purge all messages from an SQS queue |
| `aws secretsmanager list-secrets` | List all secrets |
| `aws secretsmanager create-secret` | Create a new secret |
| `aws secretsmanager get-secret-value` | Retrieve a secret value |
| `aws secretsmanager put-secret-value` | Update a secret value |
| `aws secretsmanager delete-secret` | Delete a secret |
| `aws secretsmanager rotate-secret` | Rotate a secret |
| `aws ssm get-parameter` | Get an SSM parameter value |
| `aws ssm put-parameter` | Create or update an SSM parameter |
| `aws ssm get-parameters` | Get multiple SSM parameters |
| `aws ssm get-parameters-by-path` | Get SSM parameters by path |
| `aws ssm delete-parameter` | Delete an SSM parameter |
| `aws ssm describe-parameters` | List SSM parameters |
| `aws ssm start-session` | Start an SSM session to an instance |
| `aws ssm send-command` | Run a command on managed instances |
| `aws ssm list-commands` | List SSM command invocations |
| `aws kms list-keys` | List all KMS keys |
| `aws kms create-key` | Create a new KMS key |
| `aws kms encrypt` | Encrypt data using a KMS key |
| `aws kms decrypt` | Decrypt data using a KMS key |
| `aws ecr get-login-password` | Get ECR registry login password |
| `aws ecr describe-repositories` | List ECR repositories |
| `aws ecr create-repository` | Create an ECR repository |
| `aws ecr delete-repository` | Delete an ECR repository |
| `aws ecr list-images` | List images in an ECR repository |
| `aws ecr describe-images` | Describe images in a repository |
| `aws ecr batch-delete-image` | Delete images from a repository |
| `aws ecr get-repository-policy` | Get ECR repository policy |
| `aws ecr set-repository-policy` | Set ECR repository policy |
| `aws ecr put-lifecycle-policy` | Set image lifecycle policy |
| `aws ecr get-lifecycle-policy` | Get image lifecycle policy |
| `aws apigateway get-rest-apis` | List REST APIs |
| `aws apigateway create-rest-api` | Create a REST API |
| `aws apigateway delete-rest-api` | Delete a REST API |
| `aws apigateway get-resources` | List API resources |
| `aws apigateway create-resource` | Create an API resource |
| `aws apigateway put-method` | Add a method to a resource |
| `aws apigateway put-integration` | Set up a method integration |
| `aws apigateway create-deployment` | Deploy an API to a stage |
| `aws apigateway get-stages` | List API deployment stages |
| `aws apigatewayv2 get-apis` | List HTTP and WebSocket APIs |
| `aws apigatewayv2 create-api` | Create an HTTP or WebSocket API |
| `aws apigatewayv2 get-routes` | List API routes |
| `aws ce get-cost-and-usage` | Get AWS cost and usage data |
| `aws ce get-cost-forecast` | Get cost forecast |
| `aws ce get-dimension-values` | Get cost dimension values |
| `sam init` | Initialize a new SAM application |
| `sam build` | Build a SAM application |
| `sam deploy` | Deploy a SAM application |
| `sam local invoke` | Invoke a Lambda function locally |
| `sam local start-api` | Start a local API Gateway |
| `sam logs` | Fetch Lambda function logs |
| `sam validate` | Validate a SAM template |
| `sam package` | Package a SAM application |
| `cdk init` | Initialize a new CDK project |
| `cdk synth` | Synthesize a CloudFormation template |
| `cdk deploy` | Deploy a CDK stack |
| `cdk diff` | Compare deployed stack with local |
| `cdk destroy` | Destroy a CDK stack |
| `cdk bootstrap` | Bootstrap CDK in an AWS account |
| `cdk ls` | List all CDK stacks |

## Practice & Resources

| Resource | Link |
|----------|------|
| **Practice AWS CLI interactively** | [Open Terminal](https://technoscripts.com/cli/aws-cli/?utm_source=github&utm_medium=repository&utm_campaign=cli-practice) |
| **Download PDF Cheatsheet** | [Get Cheatsheet](https://technoscripts.com/command-playground/cheatsheet/aws-cli-commands/?utm_source=github&utm_medium=repository&utm_campaign=cheatsheet) |
| **Typing Practice** | [Type AWS CLI Commands](https://technoscripts.com/command-playground/typing-practice/aws-cli/?utm_source=github&utm_medium=repository&utm_campaign=typing) |
| **All 105+ CLI Tools** | [Browse Tools Directory](https://technoscripts.com/command-playground/?utm_source=github&utm_medium=repository&utm_campaign=tools-directory) |

---

*Part of the [CLI Commands Cheatsheet](../README.md) collection by [TechnoScripts](https://technoscripts.com/?utm_source=github&utm_medium=repository&utm_campaign=tool-page)*
