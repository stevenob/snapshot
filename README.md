# snapshotanalyzer

Project to analyze AWS EC2 instances

## About

Uses boto3 to manage AWS EC2 instance snapshots.

## Configuring

shotty uses the configuration file created by the AWS cli...

`aws configure --profile shotty`

## Running

`pipenv run "python shotty/shotty.py <command> <subcommand>
<--project=PROJECT>"`

*command* is instances, volumes, or snapshots
*subcommand* - depends on command
*project* is optional
 
