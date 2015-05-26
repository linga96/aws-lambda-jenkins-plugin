# aws-lambda-jenkins-plugin

[![Build Status](https://jenkins.ci.cloudbees.com/buildStatus/icon?job=plugins/aws-lambda-plugin)](https://jenkins.ci.cloudbees.com/job/plugins/job/aws-lambda-plugin/)

This plugins adds a post build step that uploads a file or folder to AWS Lambda.

- Create AWS IAM user for use with this plugin. Must have permissions to upload a Lambda deployment package.
- Select "Deploy into Lambda" under "Add post-build step"
- Fill in the fields (description is optional)
  - For more info click on the question marks next to the input fields

![Build step config](https://raw.github.com/XT-i/aws-lambda-jenkins-plugin/master/img/build-step-config.png)

When the Lambda deployment package has been uploaded succesfully a Lambda icon will appear on the build page.