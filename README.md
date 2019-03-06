# libre-office-lambda-layer

Just contains `@shelf/aws-lambda-libreoffice` which is normally an 83MB package and can be deployed as a lambda layer using Serverless

## Deployment

**Prerequisite**
Serverless is installed globally. This can be done with `npm install -g serverless`

1. Run `cd libre-office-layer/nodejs && npm install --production && cd ../..`
1. Run `sls deploy`
