### 🪭 AWS RDS PostgreSQL Monitoring with Datadog APM

🔰 **[ GET STARTED Free 14 Days of unlimited monitoring]** with Datadog 🍀 <br />
&emsp;&emsp;Started: 2024, 14 Oct 16:48 WIB

- **Register:** <br />
  URL `https://www.datadoghq.com`

  <details><summary>🟠 Overview - registration (Free Trial)</summary>
    <div align="left">
    <img src="./gambar-petunjuk/ss_datadog_getstarted_001.png" alt="ss_datadog" style="display: block; margin: 0 auto;"> <br /><br />
    <img src="./gambar-petunjuk/ss_datadog_getstarted_002.png" alt="ss_datadog" style="display: block; margin: 0 auto;"> <br /><br />
    <img src="./gambar-petunjuk/ss_datadog_getstarted_003.png" alt="ss_datadog" style="display: block; margin: 0 auto;"> 
    </div><br /><hr />
  </details>

&nbsp;

🍀 **[ Preparation ] restricted-copies:**
<details><summary>🟠 001 - Overview - AWS Billing ( Early start )</summary>
<div align="left">
<br />
<img src="./gambar-petunjuk/ss_aws_abumuhammadbabah2019_001.png" alt="ss_aws" style="display: block; margin: 0 auto;">
</div><br /><hr />
</details>

<details><summary>🟠 002 - Overview - AWS RDS - Create Database ✳️</summary>
<div align="left">
<br />
<img src="./gambar-petunjuk/ss_aws_abumuhammadbabah2019_002.png" alt="ss_aws" style="display: block; margin: 0 auto;"> <br /><br />
<img src="./gambar-petunjuk/ss_aws_abumuhammadbabah2019_003.png" alt="ss_aws" style="display: block; margin: 0 auto;"> <br /><br />
<img src="./gambar-petunjuk/ss_aws_abumuhammadbabah2019_004.png" alt="ss_aws" style="display: block; margin: 0 auto;"> <br /><br />
<img src="./gambar-petunjuk/ss_aws_abumuhammadbabah2019_005.png" alt="ss_aws" style="display: block; margin: 0 auto;"> <br /><br />
<img src="./gambar-petunjuk/ss_aws_abumuhammadbabah2019_006.png" alt="ss_aws" style="display: block; margin: 0 auto;"> <br /><br />
<img src="./gambar-petunjuk/ss_aws_abumuhammadbabah2019_007.png" alt="ss_aws" style="display: block; margin: 0 auto;"> <br /><br />
<img src="./gambar-petunjuk/ss_aws_abumuhammadbabah2019_008.png" alt="ss_aws" style="display: block; margin: 0 auto;"> <br /><br />
<img src="./gambar-petunjuk/ss_aws_abumuhammadbabah2019_009.png" alt="ss_aws" style="display: block; margin: 0 auto;"> <br /><br />
<img src="./gambar-petunjuk/ss_aws_abumuhammadbabah2019_010.png" alt="ss_aws" style="display: block; margin: 0 auto;"> 
</div><br /><hr />
</details>

<details><summary>🟠 003 - Overview - AWS RDS - Modify Configuration Database</summary>
<div align="left">
<br />
<img src="./gambar-petunjuk/ss_aws_abumuhammadbabah2019_011.png" alt="ss_aws" style="display: block; margin: 0 auto;"> <br /><br />
<img src="./gambar-petunjuk/ss_aws_abumuhammadbabah2019_012.png" alt="ss_aws" style="display: block; margin: 0 auto;"> 
</div><br />
Notes: <br />
Modify the public access capability on the database only for testing connected only (before using EC2 instance later).
<hr />
</details>

<details><summary>🟠 004 - Overview - VPC Security Group ( inbound rules ) ✳️ 💰</summary>
<div align="left">
<br />
<img src="./gambar-petunjuk/ss_aws_abumuhammadbabah2019_013.png" alt="ss_aws" style="display: block; margin: 0 auto;"> <br /><br />
<img src="./gambar-petunjuk/ss_aws_abumuhammadbabah2019_014.png" alt="ss_aws" style="display: block; margin: 0 auto;"> <br /><br />
<img src="./gambar-petunjuk/ss_aws_abumuhammadbabah2019_015.png" alt="ss_aws" style="display: block; margin: 0 auto;"> <br /><br />
<img src="./gambar-petunjuk/ss_aws_abumuhammadbabah2019_016.png" alt="ss_aws" style="display: block; margin: 0 auto;"> 
</div><br />
Notes: <br />
The inbound setting in the security-group can be removed later after there is a connection between the instance and the rds database. 
This is only for testing rds database access from the outside.
<hr />
</details>

<details><summary>🟠 005 - Overview - DBeaver - Connection Test</summary>
<div align="left">
<br />
<img src="./gambar-petunjuk/ss_dbeaver_abumuhammadbabah2019.png" alt="ss_aws" style="display: block; margin: 0 auto;"> 
</div><br /><hr />
</details>

&nbsp;

**[ Datadog Account Access ]** <br />
https://ap1.datadoghq.com

<details><summary>🟠 006 - Overview - Datadog - Login Access Console</summary>
<div align="left">
<br />
<img src="./gambar-petunjuk/ss_datadog_baba_001.png" alt="ss_datadog" style="display: block; margin: 0 auto;"> <br /><br />
<img src="./gambar-petunjuk/ss_datadog_baba_002.png" alt="ss_datadog" style="display: block; margin: 0 auto;"> 
</div><br /><hr />
</details>

<details><summary>🟠 007 - Overview - Datadog - Integration ( AWS )</summary>
<div align="left">
<br />
<img src="./gambar-petunjuk/ss_datadog_baba_003.png" alt="ss_datadog" style="display: block; margin: 0 auto;"> <br /><br />
<img src="./gambar-petunjuk/ss_datadog_baba_004.png" alt="ss_datadog" style="display: block; margin: 0 auto;"> <br /><br />
<img src="./gambar-petunjuk/ss_datadog_baba_005.png" alt="ss_datadog" style="display: block; margin: 0 auto;"> 
</div><br /><hr />
</details>

<details><summary>🟠 008 - Overview - Datadog - Integration - View Documentation ( Site: API )</summary>
<div align="left">
<br />
<img src="./gambar-petunjuk/ss_datadog_baba_006.png" alt="ss_datadog" style="display: block; margin: 0 auto;"> <br /><br />
⌘ AWS External ID: cc5c44*******************d7aafd0
<img src="./gambar-petunjuk/ss_datadog_baba_007.png" alt="ss_datadog" style="display: block; margin: 0 auto;"> <br />
<details><summary>AWS integration IAM policy</summary>
<pre>
{
    "Version": "2012-10-17",
    "Statement": [
        {
            "Action": [
                "apigateway:GET",
                "autoscaling:Describe*",
                "backup:List*",
                "budgets:ViewBudget",
                "cloudfront:GetDistributionConfig",
                "cloudfront:ListDistributions",
                "cloudtrail:DescribeTrails",
                "cloudtrail:GetTrailStatus",
                "cloudtrail:LookupEvents",
                "cloudwatch:Describe*",
                "cloudwatch:Get*",
                "cloudwatch:List*",
                "codedeploy:List*",
                "codedeploy:BatchGet*",
                "directconnect:Describe*",
                "dynamodb:List*",
                "dynamodb:Describe*",
                "ec2:Describe*",
                "ec2:GetTransitGatewayPrefixListReferences",
                "ec2:SearchTransitGatewayRoutes",
                "ecs:Describe*",
                "ecs:List*",
                "elasticache:Describe*",
                "elasticache:List*",
                "elasticfilesystem:DescribeFileSystems",
                "elasticfilesystem:DescribeTags",
                "elasticfilesystem:DescribeAccessPoints",
                "elasticloadbalancing:Describe*",
                "elasticmapreduce:List*",
                "elasticmapreduce:Describe*",
                "es:ListTags",
                "es:ListDomainNames",
                "es:DescribeElasticsearchDomains",
                "events:CreateEventBus",
                "fsx:DescribeFileSystems",
                "fsx:ListTagsForResource",
                "health:DescribeEvents",
                "health:DescribeEventDetails",
                "health:DescribeAffectedEntities",
                "kinesis:List*",
                "kinesis:Describe*",
                "lambda:GetPolicy",
                "lambda:List*",
                "logs:DeleteSubscriptionFilter",
                "logs:DescribeLogGroups",
                "logs:DescribeLogStreams",
                "logs:DescribeSubscriptionFilters",
                "logs:FilterLogEvents",
                "logs:PutSubscriptionFilter",
                "logs:TestMetricFilter",
                "oam:ListSinks",
                "oam:ListAttachedLinks",
                "organizations:Describe*",
                "organizations:List*",
                "rds:Describe*",
                "rds:List*",
                "redshift:DescribeClusters",
                "redshift:DescribeLoggingStatus",
                "route53:List*",
                "s3:GetBucketLogging",
                "s3:GetBucketLocation",
                "s3:GetBucketNotification",
                "s3:GetBucketTagging",
                "s3:ListAllMyBuckets",
                "s3:PutBucketNotification",
                "ses:Get*",
                "sns:List*",
                "sns:Publish",
                "sns:GetSubscriptionAttributes",
                "sqs:ListQueues",
                "states:ListStateMachines",
                "states:DescribeStateMachine",
                "support:DescribeTrustedAdvisor*",
                "support:RefreshTrustedAdvisorCheck",
                "tag:GetResources",
                "tag:GetTagKeys",
                "tag:GetTagValues",
                "wafv2:ListLoggingConfigurations",
                "wafv2:GetLoggingConfiguration",
                "xray:BatchGetTraces",
                "xray:GetTraceSummaries"
            ],
            "Effect": "Allow",
            "Resource": "*"
        }
    ]
}
</pre>
</details>
<br />
⌘ Datadog Site: API <br />
⌘ Account ID Datadog: 417141415827
<img src="./gambar-petunjuk/ss_datadog_baba_008_revision_1.png" alt="ss_datadog" style="display: block; margin: 0 auto;"> <br /><br />
</div><br /><hr />
</details>

<details><summary>🟠 009 - Overview - AWS IAM - Policies ✳️</summary>
<br />
<br />
⌘ Create policy (IAM) name: DatadogIntegrationPolicy
<br />
<div align="left">
<img src="./gambar-petunjuk/ss_aws_abumuhammadbabah2019_017.png" alt="ss_aws" style="display: block; margin: 0 auto;"> <br /><br />
<img src="./gambar-petunjuk/ss_aws_abumuhammadbabah2019_018.png" alt="ss_aws" style="display: block; margin: 0 auto;"> <br /><br />
<img src="./gambar-petunjuk/ss_aws_abumuhammadbabah2019_019.png" alt="ss_aws" style="display: block; margin: 0 auto;"> <br /><br />
<img src="./gambar-petunjuk/ss_aws_abumuhammadbabah2019_020.png" alt="ss_aws" style="display: block; margin: 0 auto;"> <br /><br />
<img src="./gambar-petunjuk/ss_aws_abumuhammadbabah2019_021.png" alt="ss_aws" style="display: block; margin: 0 auto;"> <br /><br />
<img src="./gambar-petunjuk/ss_aws_abumuhammadbabah2019_022.png" alt="ss_aws" style="display: block; margin: 0 auto;"> <br /><br />
<img src="./gambar-petunjuk/ss_aws_abumuhammadbabah2019_023.png" alt="ss_aws" style="display: block; margin: 0 auto;"> <br /><br />
</div><br /><hr />
</details>

