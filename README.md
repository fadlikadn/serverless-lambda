# Command AWS Lambda function in SErverless

## Create Command Sample
- NodeJS  : run `serverless create --template aws-nodejs --path nodejs-example`
- Java  : run `serverless create --template aws-java-maven --path java-maven-example`
- C# : run `serverless create --template aws-csharp --path csharp-example`

## S3 Thumbnail Service
- Install Serverless Python Plugin : `serverless plugin install -n serverless-python-requirements` (https://www.npmjs.com/package/serverless-python-requirements)
- Deploy with run `serverless deploy -v`

### Step
1. run through the code python
2. understand serverless.yml
3. analyze the IAM role
4. test the function

- S3 events
- Function timeouts and memory
- IAM Permissions (access S3 from Lambda)
- Plugins to deploy Python Dependencies (need to have docker installed)
- Custom Variables
- Environment Variables

## Invoke service from CLI
Run `serverless invoke -f s3-thumbnail-generator --log`
