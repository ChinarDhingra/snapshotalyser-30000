# snapshotalyser-30000

Project to manage EC2 instances snapshots.

##About

This project is a demo, and uses boto3 to manage AWS EC@ instance snapshots.

##Configuring

shotty uses configuration file created by the AWS cli. e.g.

`aws configure --profile shotty`

##Running

`pipenv run "python shotty/shotty.py <command> <subcommand>
<--project =PROJECT>"`

*command* is instances, volumes, and snapshots.
*subcommand* - depends on command
*project* is optional
