# AWS Dumping Ground

## AWS Dev Setup

* [Install Python + PIP + AWS CLI](https://docs.aws.amazon.com/cli/latest/userguide/awscli-install-windows.html#awscli-install-windows-pip)
* [Update PIP](python -m pip install --upgrade pip)
* [Install SSH client for connecting to EC2 instances](PuTTY)(https://www.putty.org/)

## Cloud Formation Examples

Go into Cloud Formation and "Create New Stack" > "Design Template" and then copy/paste CF templates into Editor.

### Web Server using EC2 in a custom VPC
`simple_web_server_vpc.yaml` stack was created following [this AWS Walkthrough.](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/working-with-templates-cfn-designer-walkthrough-createbasicwebserver.html)

### API Gateway + Lambda
`api-lambda.template.yaml` stack was create following [this blog post.](https://blog.jayway.com/2016/08/17/introduction-to-cloudformation-for-api-gateway/)