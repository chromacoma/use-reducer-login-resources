# Serverless Starter - Serverless Resources

### Description

Base resources for a serverless project running on AWS. Sets up Cognito and IAM for auth, a DynamoDB users table, and an s3 bucket for user files

#### Usage

To use this repo locally you need to have the [Serverless framework](https://serverless.com) installed.

```bash
$ npm install serverless -g
```

Clone this repo.

```bash
$ git clone https://github.com/chromacoma/serverless-starter-serverless-resources
```

Replace the following constants:

```bash
__PACKAGE_NAME__
__AWS_REGION__
__USERS_TABLE_NAME__
__FILES_BUCKET_NAME__
```

Go to one of the services in the `services/` dir.

And run this to deploy to your AWS account.

```bash
$ serverless deploy
```

Once you deploy the resources in this repo, head over to [the accompanying api repo](https://github.com/chromacoma/serverless-starter-api) to deploy the API services.

#### Maintainers

Comments and / or pull requests are welcomed!

[email]: mailto:john@minml.net
