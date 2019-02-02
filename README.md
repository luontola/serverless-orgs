# serverless-orgs

This project will be developed in an experimental programming mob meetup, which will convene weekly and continue from where it was left last week.

## Project Goal

User registration service.
[Event sourced](https://martinfowler.com/eaaDev/EventSourcing.html).
[Serverless](https://medium.com/@PaulDJohnston/a-simple-definition-of-serverless-8492adfb175a).

## Problem Description

There are multiple organizations, which have multiple members. Organization admin can add/invite members to an organization. Members can have permissions granted to them. Members can be deleted in a GDPR compliant way.

## Technology Stack

DynamoDB and S3 for persistence. The code runs in AWS Lambda using JavaScript/ClosureScript (or Clojure with [Substrate VM](https://www.graalvm.org/docs/reference-manual/aot-compilation/)). Authentication using AWS Cognito and OpenID. Deployment with AWS CDK. Frontend with React.
