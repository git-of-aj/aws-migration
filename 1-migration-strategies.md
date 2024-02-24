https://aws.amazon.com/blogs/enterprise-strategy/6-strategies-for-migrating-applications-to-the-cloud/
- AWS Docs - https://docs.aws.amazon.com/prescriptive-guidance/latest/large-migration-guide/migration-strategies.html

## Green field vs Brownfield
- [Capgemini](https://www.capgemini.com/se-en/insights/expert-perspectives/confusion-in-the-cloud-greenfield-or-brownfield/)

## How to Migrate:
[How to Migrate](https://aws.amazon.com/cloud-migration/how-to-migrate/)

## Cloud Migrations Tool Categories:
[Cloud Migrations Tool Categories](https://aws.amazon.com/products/migration-and-transfer/)

## MAP Funding: 
https://aws.amazon.com/migration-acceleration-program/

## AWS CAF

## 7 R aka migration strategy:
**Example here :**
![](https://docs.aws.amazon.com/images/prescriptive-guidance/latest/application-portfolio-assessment-guide/images/7Rs-DecisionTree-baseModel.png)
- [Read Here](https://aws.amazon.com/blogs/enterprise-strategy/6-strategies-for-migrating-applications-to-the-cloud/)

## Cut-Over Etc B4 MGN Service

## JOe
Week 2 - Mobilisation Team
***************************

Phases of Project Delivery
(1) Assessment / Discovery Phase 
    - Cost Limit : 60,000 USD
    - Workloads are identified in this phase

(2) Mobilisation Phase - Max (POC Phase)
    - Cost Limit : 400,000 USD  (POC Phase) 
    - Project Duration : 4 to 6 months Approx
    - Foundations are build 
      - Deciding Architecture
      - Best practices
      - Security
      - Landing Zone
      - Enablement (Client)
      - Compliance Governance 
      - Audit
      - Automation
      

Phase 1 : Create Business Case
Phase 2 : Create a Security Baseline Document
Phase 3 : Monitoring, Logging and Reporting Plan
Phase 4 : Automation Plan
Phase 5 : Landing Zone
Phase 6 : Design target architectures 
Phase 7 : Migration Strategy and Plans

Links:

https://docs.aws.amazon.com/prescriptive-guidance/latest/strategy-migration/mobilize-phase.html
https://docs.aws.amazon.com/prescriptive-guidance/latest/patterns/migration-pattern-list.html



6 R 

SOW -- ms docs
project Plan proposal --> presales 
-- 
1. Assesment phase 55k
- what we have now ?
2. Mobile phase (depends generally min 6 month) => upto 400k max cap  ==> cosulting partners suffer if you strech too long
  - bigger ARR ==> big time taken
- deep discovery --> retain or Retire 
- landing zone ==> no UAT / Prd / SIT ==> Only 1 ==> genrally takes 90 days
* not more than 200 vm => don't create a landing zone
- checklist of requirements while creating a landing zone
- war
- security risk and compliance review 
- automation needs requiremnet check
sample poc -- stateless and stateful app ==> customer tells these are non critical apps ==> move them
- Rehost Here 

Next Step: Migration Plan ==> 25% of ARR from AWS + Customer Pays if this amt is less
- refactor + modernise == here more money + time you get 
- replatform 
- repurchase

revised 
AWS clculator 

AWS Migration Acceleration Program (MAP)

output of dicovery assesment phase as input to mobiise

Azure BCIF


- Terraform Cloud and Vault as a policy standard
- Sentinel policies of Terraform Cloud
- Vault Standard - for secret management

====================


https://github.com/aws-samples/aws-three-tier-web-architecture-workshop


https://www.flexera.com/blog/it-asset-management/evolving-the-ecosystem-with-ibm/

https://docs.google.com/document/d/1qC2irioUtVcFqYJ7QPDYX6EuBXnIA7Xu/mobilebasic

https://gitlab.com/tfe.poc1/tfe2-demo

https://app.diagrams.net/#G1pmOloRLxsjjJD45oCpgVjGVy7dX32Tdh

===============================================================

Patching Prod and non prod vm using ivanty and azure update 

---------------------------------------------------------------

## The Executives Migration 
**WHy you need to Migrate?**
![](https://docs.aws.amazon.com/images/prescriptive-guidance/latest/strategy-large-scale-migrations/images/scope-strategy-timeline.png)

1. Your application teams want to implement new CI/CD pipelines, deploy the latest application stacks, or modernize legacy platforms that are out of support.

2. Your infrastructure team must get out of an aging data center quickly before the lease expires and the provider turns the power off.

3. The board has decided that you need to move to the cloud as a strategic direction, allowing for a fast pace of change in the business’s future.

# AWS Migration Tools 
1. **Discovery**:
- AWS ADS requires you do to task while Migration evaluator gives  a ready to use business case
- Key Differences:

- Purpose: Migration Evaluator focuses on optimizing costs, performance, and resource utilization before migration, while AWS ADS focuses on discovering and collecting information about your on-premises environment to facilitate migration planning.
- Functionality: Migration Evaluator provides recommendations for optimizing infrastructure, whereas AWS ADS focuses on discovery, dependency mapping, and application profiling.
- Integration: While AWS ADS integrates with other AWS migration services like SMS, Migration Evaluator is a standalone tool focused on analysis and recommendations

-----------------------

**AWS ADS:** Part of AWS Migration Hub 
- [AWS Docs](https://docs.aws.amazon.com/migrationhub/latest/ug/whatishub.html)

