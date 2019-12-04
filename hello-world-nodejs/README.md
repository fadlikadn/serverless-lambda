# Setup AWS Lambda Serverless

## Install Serverless
`npm install -g serverless`

## Command
Use `serverless` or `sls`

### setup serverless
`serverless config credentials --provider aws --key XXX --secret YYY --profile serverless-admin`

### Create sample serverless
`serverless create --template aws-nodejs --path hello-world-nodejs`

### Deploy serverless
`serverless deploy`

### Running serverless from CLI :
`serverless invoke -f hello -l`

### Update serverless (upgrade) :
`serverless deploy function -f hello`

### Fetching function logs from the CLI :
`serverless logs -f hello -t`

### Remove the function from S3 and Lambda
`serverless remove`

## Reference : 
- https://www.packtpub.com/networking-and-servers/aws-lambda-and-serverless-framework-hands-learning
- https://serverless.com/