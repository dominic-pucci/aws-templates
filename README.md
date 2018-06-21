# AWS Free Tier Wordpress Installation

Single Template Wordpress Installation using AWS CloudFormation. This should be entirely within the free tier. This was cloned, converted to YAML, and modified from a template that AWS provides here:
https://s3-eu-west-1.amazonaws.com/cloudformation-templates-eu-west-1/WordPress_Multi_AZ.template

### Prerequisites

1. An AWS Account
2. (Optional) An S3 bucket to store this template in. Otherwise you can just upload the template via the CloudFormation console.
3. The following parameters (easier to gather beforehand):

```
EC2 KeyPair Name
Your Current IP address (Google Search for What's My IP)
```

## Deployment

1. Log into your AWS account and navigate to the CloudFormation console
2. Select Create Stack
3. Input the necessary parameters
4. Click Next until you reach the final step, and then click Create
5. Once the stack status reads CREATE_COMPLETE, select your stack and navigate to the Outputs tab, where a link to your WordPress site will be available.
6. Navigate to that link and complete the WordPress browser installation
