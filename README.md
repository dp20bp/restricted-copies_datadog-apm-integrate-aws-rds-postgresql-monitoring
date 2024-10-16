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
⌘ Create policy (IAM) name: DatadogIntegrationPolicy
<br />
<div align="left">
<img src="./gambar-petunjuk/ss_aws_abumuhammadbabah2019_017.png" alt="ss_aws" style="display: block; margin: 0 auto;"> <br /><br />
<img src="./gambar-petunjuk/ss_aws_abumuhammadbabah2019_018.png" alt="ss_aws" style="display: block; margin: 0 auto;"> <br /><br />
<img src="./gambar-petunjuk/ss_aws_abumuhammadbabah2019_019.png" alt="ss_aws" style="display: block; margin: 0 auto;"> <br /><br />
<img src="./gambar-petunjuk/ss_aws_abumuhammadbabah2019_020.png" alt="ss_aws" style="display: block; margin: 0 auto;"> <br /><br />
<img src="./gambar-petunjuk/ss_aws_abumuhammadbabah2019_021.png" alt="ss_aws" style="display: block; margin: 0 auto;"> <br /><br />
<img src="./gambar-petunjuk/ss_aws_abumuhammadbabah2019_022.png" alt="ss_aws" style="display: block; margin: 0 auto;"> <br /><br />
<img src="./gambar-petunjuk/ss_aws_abumuhammadbabah2019_023.png" alt="ss_aws" style="display: block; margin: 0 auto;"> 
</div><br /><hr />
</details>

<details><summary>🟠 010 - Overview - AWS IAM - Roles ✳️</summary>
<br />
⌘ Create role (IAM) name: DatadogIntegrationRole
<br />
<div align="left">
<img src="./gambar-petunjuk/ss_aws_abumuhammadbabah2019_024.png" alt="ss_aws" style="display: block; margin: 0 auto;"> <br /><br />
<img src="./gambar-petunjuk/ss_aws_abumuhammadbabah2019_025_revision_1.png" alt="ss_aws" style="display: block; margin: 0 auto;"> <br /><br />
<img src="./gambar-petunjuk/ss_aws_abumuhammadbabah2019_026.png" alt="ss_aws" style="display: block; margin: 0 auto;"> <br /><br />
<img src="./gambar-petunjuk/ss_aws_abumuhammadbabah2019_027_revision_1.png" alt="ss_aws" style="display: block; margin: 0 auto;"> <br /><br />
<img src="./gambar-petunjuk/ss_aws_abumuhammadbabah2019_028.png" alt="ss_aws" style="display: block; margin: 0 auto;"> 
</div><br /><hr />
</details>

<details><summary>🟠 011 - Overview - Datadog - Integration ( Continued )</summary>
<div align="left">
<br />
<img src="./gambar-petunjuk/ss_aws_abumuhammadbabah2019_029.png" alt="ss_aws" style="display: block; margin: 0 auto;"> <br />
⌘ AWS Account ID: 730335453692 <br />
<br />
<img src="./gambar-petunjuk/ss_datadog_baba_009.png" alt="ss_datadog" style="display: block; margin: 0 auto;"> <br />
<br />
🆗 **[Save anyway]** <br />
<img src="./gambar-petunjuk/ss_datadog_baba_009.png" alt="ss_datadog" style="display: block; margin: 0 auto;"> <br /><br />
<img src="./gambar-petunjuk/ss_datadog_baba_010.png" alt="ss_datadog" style="display: block; margin: 0 auto;"> <br /><br />
<img src="./gambar-petunjuk/ss_datadog_baba_011.png" alt="ss_datadog" style="display: block; margin: 0 auto;"> <br /><br />
<img src="./gambar-petunjuk/ss_datadog_baba_012.png" alt="ss_datadog" style="display: block; margin: 0 auto;"> 
</div><br /><hr />
</details>

<details><summary>🟠 012 - Overview - Datadog - (Check) Database Monitoring</summary>
<div align="left">
<br />
<img src="./gambar-petunjuk/ss_datadog_baba_013.png" alt="ss_datadog" style="display: block; margin: 0 auto;"> <br /><br />
<img src="./gambar-petunjuk/ss_datadog_baba_014.png" alt="ss_datadog" style="display: block; margin: 0 auto;"> <br /><br />
<img src="./gambar-petunjuk/ss_aws_abumuhammadbabah2019_030.png" alt="ss_aws" style="display: block; margin: 0 auto;"> <br /><br />
<img src="./gambar-petunjuk/ss_aws_abumuhammadbabah2019_031.png" alt="ss_aws" style="display: block; margin: 0 auto;"> <br /><br />
<img src="./gambar-petunjuk/ss_aws_abumuhammadbabah2019_032.png" alt="ss_aws" style="display: block; margin: 0 auto;">
</div><br /><hr />
</details>

<details><summary>🟠 013 - Overview - AWS Create Instance ( EC2 ) ✳️</summary>
<div align="left">
<br />
<img src="./gambar-petunjuk/ss_aws_abumuhammadbabah2019_033.png" alt="ss_aws" style="display: block; margin: 0 auto;"> <br /><br />
<img src="./gambar-petunjuk/ss_aws_abumuhammadbabah2019_034.png" alt="ss_aws" style="display: block; margin: 0 auto;"> <br /><br />
<img src="./gambar-petunjuk/ss_aws_abumuhammadbabah2019_035.png" alt="ss_aws" style="display: block; margin: 0 auto;"> <br /><br />
<img src="./gambar-petunjuk/ss_aws_abumuhammadbabah2019_036.png" alt="ss_aws" style="display: block; margin: 0 auto;"> <br /><br />
<img src="./gambar-petunjuk/ss_aws_abumuhammadbabah2019_037.png" alt="ss_aws" style="display: block; margin: 0 auto;"> <br /><br />
<img src="./gambar-petunjuk/ss_aws_abumuhammadbabah2019_038.png" alt="ss_aws" style="display: block; margin: 0 auto;"> <br /><br />
<img src="./gambar-petunjuk/ss_aws_abumuhammadbabah2019_039.png" alt="ss_aws" style="display: block; margin: 0 auto;"> 
</div><br /><hr />
</details>

&nbsp;

[ Instance Running State ] <br />
Public IPv4: 3.107.86.65 
<pre>
[ SSH Connection ]
❯ ssh -i "./Files/datadog-ec2.pem" ec2-user@ec2-3-107-86-65.ap-southeast-2.compute.amazonaws.com
</pre>

-   <details><summary>[ Test Connection to instance ]</summary>
    <pre>
    ❯ ssh -i "./Files/datadog-ec2.pem" ec2-user@ec2-3-107-86-65.ap-southeast-2.compute.amazonaws.com <br />
    The authenticity of host 'ec2-3-107-86-65.ap-southeast-2.compute.amazonaws.com (3.107.86.65)' can't be established.
    ED25519 key fingerprint is SHA256:7A+t/fzJgVbypjTiCZYYFsatEW+TGQZKmaHINKElRc4.
    This key is not known by any other names
    Are you sure you want to continue connecting (yes/no/[fingerprint])? yes
    Warning: Permanently added 'ec2-3-107-86-65.ap-southeast-2.compute.amazonaws.com' (ED25519) to the list of known hosts.
    @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
    @         WARNING: UNPROTECTED PRIVATE KEY FILE!          @
    @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
    Permissions 0644 for './Files/datadog-ec2.pem' are too open.
    It is required that your private key files are NOT accessible by others.
    This private key will be ignored.
    Load key "./Files/datadog-ec2.pem": bad permissions
    ec2-user@ec2-3-107-86-65.ap-southeast-2.compute.amazonaws.com: Permission denied (publickey,gssapi-keyex,gssapi-with-mic). <br /><br />
    ❯ chmod 400 ./Files/datadog-ec2.pem <br /><br />
    ❯ ssh -i "./Files/datadog-ec2.pem" ec2-user@ec2-3-107-86-65.ap-southeast-2.compute.amazonaws.com <br />
    ,     #_
    ~\_  ####_        Amazon Linux 2023
    ~~  \_#####\
    ~~     \###|
    ~~       \#/ ___   https://aws.amazon.com/linux/amazon-linux-2023
    ~~       V~' '->
        ~~~         /
        ~~._.   _/
            _/ _/
        _/m/'
    [ec2-user@ip-172-31-11-247 ~]$ 
    </pre>
    <br />
    <hr>
    </details>



