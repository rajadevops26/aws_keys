# [aws-cli](https://aws.amazon.com/cli/)
ACCESS KEY & SECURITY KEY
*************************
```

MY ACCOUNT USERNAME(LOVERAJARANI)>>>>>>>>My Security Credentials>>>>>>>Access keys (access key ID and secret access key)
---------------->>>>>>>> Create New Access Key

```

## install steps
apt install python-pip
pip install awscli
aws configure
```
AWS Access Key ID [None]: AKIAIYTLX5KKLG7JYRSA
AWS Secret Access Key [None]: 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
Default region name [None]: US East (N. Virginia)--------------------------- this is not current region for s3
Default output format [None]: json
*********************************************************
AWS Access Key ID [None]: AKIAIYTLX5KKLG7JYRSA
AWS Secret Access Key [None]: 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
Default region name [None]: us-east-1
Default output format [None]: json

```
aws s3 mb s3://raja3
aws s3 ls s3://raja3
aws s3 cp //root/abc.txt s3://raja3------------> to copy file on s3

COMMANDS
********
```
 aws help
  aws <command> help
  aws <command> <subcommand> help
```
SUBCOMMANDS
***********
```
acm                                      | acm-pca
alexaforbusiness                         | amplify
apigateway                               | apigatewaymanagementapi
apigatewayv2                             | application-autoscaling
appmesh                                  | appstream
appsync                                  | athena
autoscaling                              | autoscaling-plans
batch                                    | budgets
ce                                       | chime
cloud9                                   | clouddirectory
cloudformation                           | cloudfront
cloudhsm                                 | cloudhsmv2
cloudsearch                              | cloudsearchdomain
cloudtrail                               | cloudwatch
codebuild                                | codecommit
codepipeline                             | codestar
cognito-identity                         | cognito-idp
cognito-sync                             | comprehend
comprehendmedical                        | connect
cur                                      | datapipeline
datasync                                 | dax
devicefarm                               | directconnect
discovery                                | dlm
dms                                      | ds
dynamodb                                 | dynamodbstreams
ec2                                      | ecr
ecs                                      | efs
eks                                      | elasticache
elasticbeanstalk                         | elastictranscoder
elb                                      | elbv2
emr                                      | es
events                                   | firehose
fms                                      | fsx
gamelift                                 | glacier
globalaccelerator                        | glue
greengrass                               | guardduty
health                                   | iam
importexport                             | inspector
iot                                      | iot-data
iot-jobs-data                            | iot1click-devices
iot1click-projects                       | iotanalytics
kafka                                    | kinesis
kinesis-video-archived-media             | kinesis-video-media
kinesisanalytics                         | kinesisanalyticsv2
kinesisvideo                             | kms
lambda                                   | lex-models
lex-runtime                              | license-manager
lightsail                                | logs
machinelearning                          | macie
marketplace-entitlement                  | marketplacecommerceanalytics
mediaconnect                             | mediaconvert
medialive                                | mediapackage
mediastore                               | mediastore-data
mediatailor                              | meteringmarketplace
mgh                                      | mobile
mq                                       | mturk
neptune                                  | opsworks
opsworkscm                               | organizations
pi                                       | pinpoint
pinpoint-email                           | polly
pricing                                  | quicksight
ram                                      | rds
rds-data                                 | redshift
rekognition                              | resource-groups
resourcegroupstaggingapi                 | robomaker
route53                                  | route53domains
route53resolver                          | s3control
sagemaker                                | sagemaker-runtime
sdb                                      | secretsmanager
securityhub                              | serverlessrepo
servicecatalog                           | servicediscovery
ses                                      | shield
signer                                   | sms
sms-voice                                | snowball
sns                                      | sqs
ssm                                      | stepfunctions
storagegateway                           | sts
support                                  | swf
transcribe                               | transfer
translate                                | waf
waf-regional                             | workdocs
workmail                                 | workspaces
xray                                     | s3api
s3                                       | configure
deploy                                   | configservice
opsworks-cm                              | runtime.sagemaker
history                                  | help
```
