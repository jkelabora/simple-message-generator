simple-message-generator
========================

Sends messages to an AWS SQS queue which are designed to be consumed by: https://github.com/jkelabora/raspberry-pipeline

```
cd aws-java-sdk-1.3.30/samples/AmazonSimpleQueueService
echo "accessKey=[--INSERT--]" > AwsCredentials.properties 
echo "secretKey=[--INSERT--]" >> AwsCredentials.properties
ant -Darg0="ap-southeast-2" -Darg1="raspberry-pipeline" -Darg2="start_build" run
```
