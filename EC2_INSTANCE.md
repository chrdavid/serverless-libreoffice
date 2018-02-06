# Steps

1. Go to [Lambda Execution Environment and Available Libraries](https://docs.aws.amazon.com/lambda/latest/dg/current-supported-versions.html)
page to get the latest AMI id
2.  Click on [this link](https://console.aws.amazon.com/ec2/v2/home#Images:visibility=public-images;search=amzn-ami-hvm-2017.03.1.20170812-x86_64-gp2)
to get AMI id for your region
3. Spin up a `c5.2xlarge` spot instance with ~ 100 GB of storage attached
4. Follow the steps in `compile.sh` file in the repo