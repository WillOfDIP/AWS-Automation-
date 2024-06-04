## Aws Script for AWS Management

This Python script can be used to manage an AWS endorsement.

This provides features like :

### EC2 :

1. Create your own Key based SnapShots 
2. Delete SnapShots 
3. Delete/ Terminate any EC2 instance which does not have a user/ any specific tag 
4. stop any useless Running Ec2 instance

### RDS : 

1. delete RDS Instance
2. Delete RDS Cluster
3. Stop any useless Running RDS Cluster/Instance
4. Delete useless Snapshots 
5. Delete any RDS Instance or Cluster which does not have a specific tag with it 
6. Delete any RDS Snapshot that is older than 2 days 

These scripts can directly be used with the AWS lambda function for Automation purposes as well

## Installation

First of all install [python]("https://www.python.org/downloads/") on your system.
```
pip install boto3
```


