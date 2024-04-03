# aws-migration
⚠️⚠️⚠️ AWS MGN services creates lot of snapshots !!!!!!!!!!!!! 

# Aws executive guidebook
- Migrate first, then modernize on AWS except for 
specialized workloads that require replatforming or refactoring to migrate
- The Migration Acceleration Program (MAP) is the AWS flagship program for helping 

customers accelerate each step (assess, mobilize, migrate) o

- yor. 

A migration assessment is an automated deep evaluation of digital assets used to create a 

data-driven business case for moving to the cloud. The business case clarifies current data 

center software and infrastructure, is a tool for stakeholder alignment, and identifies cost 

saving opportunities (e.g., software licensing, infrastructure). Business cases deliver a 

comparative analysis of on-premises total cost of ownership (TCO) and projected cloud TCO. 

During an assessment, digital assets (e.g., software, servers, storage) are automatically 

discovered across all environments including on-premises data centers, edge data centers, 

carrier hotels, and colocation facilities. Inventory and utilization (e.g., CPU, memory, 

configuration, storage) data are collected for recommendation synthesis. For example, 

assessments identify cost saving opportunities like overprovisioned (underutilized) workloads 

to right-size in the cloud, idle hosts for removal, and mitigations for costly software licence

- `Migration assessment provides the business case`for moving to the cloud and helps executive 

leaders define migration objectives

- The goal of the `mobilization phase`

is to help organizations build the cloud foundations (e.g., leading, transforming, operating) to 

manage, operate, and grow mission-critical applications on AWS before workloads arrive in 

the cloud. After mobilization, customers have the tools, process, and capability to rehost at 

scale and operate in the cloud.
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
