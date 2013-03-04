simple-message-generator
========================

```
cd aws-java-sdk-1.3.30/samples/AmazonSimpleQueueService
echo "accessKey=[--INSERT--]" > AwsCredentials.properties && echo "secretKey=[--INSERT--]" >> AwsCredentials.properties
ant -Darg0="ap-southeast-2" -Darg1="raspberry-pipeline" -Darg2="start_build:2:0.5:0:0:1.0" run
```
