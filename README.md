# snapshotanalyzer
Demo Project to manage AWS EC2 instance snapshot

##  About

This project is a demo and uses boto3 to manage AWS Ec2 instances

## Configuring

shotty uses the configuration file created by the AWS cli e.g.

'aws configure --profile shotty'

## Running

'pipenv run "python shotty/shotty.py <command> <--project=PROJECT>'

*command* is list, start, or stop
*project* is optional

