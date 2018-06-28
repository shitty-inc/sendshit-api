# Sendsh.it API

This is the backend API for the [sendsh.it](https://github.com/shitty-inc/sendsh.it) file transfer service.

Written in Go and deployed to Lambda it provides endpoints to upload and retrive files from S3.

## Deployment

The API is deployed with [serverless](https://serverless.com/).

```
$ npm i -g serverless
$ npm run build && npm run deploy
```

## Testing

You can also spin up a local instance for testing with Docker and [AWS SAM](https://github.com/awslabs/aws-sam-cli).

```
$ npm install
$ npm run start
```