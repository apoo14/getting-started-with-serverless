## Getting started with serverless

This getting started series is written by the serverless developer advocate team @AWSCloud. It has been designed for developers who know how to code but are new to serverless. Follow along with blog posts, code samples, and practical exercises to learn how to build serverless applications from your local Integrated development environment (IDE).

![img](/resources/gettingstarted-developer_2.png)



### How to use this Repository

This repository is split into folders. Each folder has a corresponding blog post on the AWS serverless Compute blog. Read the blogs posts and refer back to the code samples in this repository:

| Blog Post                                                                                                                                                                                                                                                                                                                                                                 | Code               |
| :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------ |
| [Intro to serverless](https://aws.amazon.com/blogs/compute/getting-started-with-serverless-for-developers-part-1/) <br> Learn why developers need serverless technologies and which challenges serverless technologies help to solve. You deploy a simple serverless application to your AWS account that connects Slack to GitHub and see first-hand why serverless technologies sparks joy for developers.                                                     | [/Part_1](/part_1) |
| The business logic (Blog to be published 19th April 2021) <br> Learn where that business logic exists within the serverless application. You see how to extend the application by editing the business logic and learn about some of the AWS services involved.                                                                                                                                          | [/Part_2](/part_2) |
| The front door (Blog to be published 26th April 2021) <br> See how to access business logic by creating a front door to your serverless application with Amazon API Gateway. You extend the example serverless application to process an additional GitHub webhook URL. Finally, you see how Serverless applications help to reduce complexity and code by decoupling business logic from routing logic. | [/Part_3](/part_3) |


### The Application

By the end of this 3-part series you will have built a serverless application that connects GitHub and Slack together. The app will post a message to Slack when a GitHub repository has been starred or forked. The final output of which loks like the following:


| ![simple Serverless](/resources/simpleserverless.png) | ![GitHub to Slack](/resources/slackpost.png) |
| :---------------------------------------------------- | -------------------------------------------- |


## Prerequisits

To deploy this application, you need:
* The [AWS Serverless Application Model (AWS SAM CLI)](https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/serverless-sam-cli-install.html) installed with an [AWS account](https://aws.amazon.com/premiumsupport/knowledge-center/create-and-activate-aws-account/) set up.
* A GitHub account, and a repository with admin permissions.
* A [Slack](https://slack.com/) account with the ability to create apps.


# Deploy the App
Refer to [blog post part 1](https://aws.amazon.com/blogs/compute/getting-started-with-serverless-for-developers-part-1#attachment_13811) to deploy the app:


## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.

