## useful links: 
https://serverless.com/framework/docs/providers/aws/guide/quick-start/<br/>
https://serverless.com/framework/docs/providers/aws/guide/credentials/

## deploy a function to aws lambda after gaining proper credentials.
serverless deploy -v
serverless deploy function -f hello
serverless invoke -f hello -l

## fetch the logs: 
serverless logs -f hello -t

