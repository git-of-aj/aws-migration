## aws mgn 
https://docs.aws.amazon.com/mgn/latest/ug/what-is-application-migration-service.html
- Steps for AWS MGN : https://docs.aws.amazon.com/mgn/latest/ug/launching-test-gs.html
- After you have added all of your source servers and configured their launch settings, you are ready to launch a test instance. It is crucial to test the migration of your source servers to AWS prior to initiating a cutover in order to verify that your source servers function properly within the AWS environment
- DOCS FOR TEST INSTANCES: https://docs.aws.amazon.com/mgn/latest/ug/launching-test-gs.html
  
## aws dms
https://docs.aws.amazon.com/dms/latest/userguide/Welcome.html
## Assesment - AWS Mogration Hub
https://aws.amazon.com/migration-hub/features/?nc=nsb&pg=ln
**AWS Migration Evaluator:**
- **Purpose:** Provides cost estimates and insights to plan migration projects effectively.
- **Use Cases:**
  - Use when you need to estimate the cost of migrating your existing on-premises infrastructure to AWS.
  - Use when you want to assess the financial implications of different migration strategies.
  - Use as a starting point to understand the potential savings and ROI of migrating to AWS.

**AWS Migration Hub:**
- **Purpose:** Offers a single location to plan, track, and manage application migrations.
- **Use Cases:**
  - Use when you want centralized visibility and tracking of multiple migration projects.
  - Use when you need to coordinate migrations involving multiple AWS services and tools.
  - Use to monitor the progress and status of migrations across your organization.

**AWS Application Discovery Service:**
- https://docs.aws.amazon.com/application-discovery/latest/userguide/console-walkthrough.html
- **Purpose:** Helps discover and collect data about your on-premises applications and their dependencies.
- **Use Cases:**
  - Use when you need to understand the application landscape in your on-premises environment.
  - Use when planning a migration to identify interdependencies between applications and servers.
  - Use to gain insights into resource utilization, helping with right-sizing decisions.

**Real-Life Use Case:**
Imagine a large enterprise planning a migration to AWS:

1. **AWS Migration Evaluator:** 
   - They start with AWS Migration Evaluator to estimate the cost of migrating their existing on-premises infrastructure. This tool provides them with a detailed cost analysis, helping them understand the financial implications of the migration.

2. **AWS Application Discovery Service:**
   - Simultaneously, they deploy AWS Application Discovery Service in their on-premises environment. This service helps them discover and collect data about their applications, dependencies, and resource utilization.

3. **AWS Migration Hub:**
   - With the information gathered by AWS Application Discovery Service, they use AWS Migration Hub to create a centralized migration plan. They track the progress of migrating their applications and infrastructure while coordinating multiple migration projects across various teams and departments.

In this real-life scenario, all three services are used together: AWS Migration Evaluator for cost estimation, AWS Application Discovery Service for data collection and dependency analysis, and AWS Migration Hub for centralized migration project management. This holistic approach allows the enterprise to efficiently plan, execute, and monitor their migration to AWS.

## Default templates created
Every time you add a source server to Application Migration Service, its Replication settings, Launch settings and Post-launch action settings are initialized based on default templates. You can edit the default templates in the Settings page.
The next step to setting up Application Migration Service is adding your source servers by installing the AWS Replication agent on them

- Usually for VMware VMDK files can store the entire contents of a virtual machine, including the operating system, installed applications, application data, user data, and more. They essentially represent a virtual hard drive that contains all the data and configurations of a virtual machine.
