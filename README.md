# snapshotanalyzer
Demo project to manage AWS EC2 instance snapshot

## About

This project is a demo, and uses boto3 to manage AWS EC2 instance snapshots.

## Configuring

Analyzer uses the configuration file created by the AWS CLI. e.g:

`aws configure --profile analyzer`

## Running

`pipenv run python analyzer/analyzer.py <command> <--project=PROJECT>`

*command* is list, start, or stop'
*project* is optional
