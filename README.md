# Docker image with Node.js for GitLab CI on Fargate

A Docker image ready to run Node.js CI jobs with the [AWS Fargate Custom
Executor driver](https://gitlab.com/gitlab-org/ci-cd/custom-executor-drivers/fargate)
for [GitLab Runner](https://docs.gitlab.com/runner).

Based on https://gitlab.com/aws-fargate-driver-demo/docker-nodejs-gitlab-ci-fargate


With following upgrades/additions:

* NodeJS 16
* AWS SAM
* curl
* jq

