# aws-migration
⚠️⚠️⚠️ AWS MGN services creates lot of snapshots !!!!!!!!!!!!! 

# Install mariabadb
```
sudo su
yum install mariadb-server.x86_64
systemctl start mariadb
mysql_secure_installation
```
1. Homogenous Migration:
- moving into same family of database
- MYSQL on-prem to MYSQL RDS

- Rehost / Replatform

2. Heterogenous migration
move into different database family

MYSQL DB => DynamoDB (NoSQL)

MYSQL DB on Prem ==>
MS SQL or Aurora in AWS

- Refactor

## Database Migration: Amazon Linux 2023 has pre installed Mysql

* AWS SCT: Schema Conversion tool 
- Required only for heterogenous migration
- helps make compatible Schema for your target Database

AWS DMS (database Migration service): 
Performs actual Migration

Phase 1.  Create a business Case 
- Gather Customer Requirement
-  Expand Requirement 
- Proposal
- SOW
# Tools - 
1. Assesment: a: Migration Evaluator | b: 
2. Migration
3. Modernatisation
4. Data transfer

# AWS Migration Hub 
- https://docs.aws.amazon.com/migrationhub/

PHASE 7 : Actual Migration starts:
1.Discovery
2. Test
3. Cutover (Green signal to move finally)
4. Post Production support 
