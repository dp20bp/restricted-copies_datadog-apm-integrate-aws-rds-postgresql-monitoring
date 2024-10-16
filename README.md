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



<details><summary>🟠 014 - Overview - Datadog - Install Agent</summary>
<div align="left">
<br />
<img src="./gambar-petunjuk/ss_datadog_baba_015.png" alt="ss_datadog" style="display: block; margin: 0 auto;"> <br /><br />
<img src="./gambar-petunjuk/ss_datadog_baba_016.png" alt="ss_datadog" style="display: block; margin: 0 auto;"> <br /><br />
<img src="./gambar-petunjuk/ss_datadog_baba_017.png" alt="ss_datadog" style="display: block; margin: 0 auto;"> <br /><br />
<img src="./gambar-petunjuk/ss_datadog_baba_018.png" alt="ss_datadog" style="display: block; margin: 0 auto;"> <br /><br />
<br />
⌘ [API KEY]: 1ae*************************05d4
<pre>
#AGENT INSTALLATION COMMAND:
❯  DD_API_KEY=1ae*************************05d4 \
   DD_SITE="ap1.datadoghq.com" \
   bash -c "$(curl -L https://install.datadoghq.com/scripts/install_script_agent7.sh)"
</pre>
<img src="./gambar-petunjuk/ss_ssh_instance_datadog_001.png" alt="ss_ssh" style="display: block; margin: 0 auto;"> <br /><br />
<img src="./gambar-petunjuk/ss_ssh_instance_datadog_002.png" alt="ss_ssh" style="display: block; margin: 0 auto;"> <br />
<br />
<details><summary>Full details of installing dd-agent with ssh remote</summary>
<pre>
❯ ssh -i "./Files/datadog-ec2.pem" ec2-user@ec2-3-107-86-65.ap-southeast-2.compute.amazonaws.com
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
Last login: Tue Oct 15 09:34:55 2024 from 45.251.5.172
[ec2-user@ip-172-31-11-247 ~]$ DD_API_KEY=1ae*************************05d4 \
DD_SITE="ap1.datadoghq.com" \
bash -c "$(curl -L https://install.datadoghq.com/scripts/install_script_agent7.sh)"
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100 77366  100 77366    0     0  1711k      0 --:--:-- --:--:-- --:--:-- 1717k <br />
* Datadog Agent 7 install script v1.35.4 <br />
/usr/bin/systemctl <br />
* Installing YUM sources for Datadog <br />
Cache was expired
17 files removed
  Installing package(s): datadog-agent <br />
Datadog, Inc.                                   7.4 kB/s | 801  B     00:00    
Datadog, Inc.                                    48 kB/s | 1.7 kB     00:00    
Importing GPG key 0xB01082D3:
 Userid     : "Datadog, Inc. RPM key (2023-04-20) (RPM key) <package+rpmkey@datadoghq.com>"
 Fingerprint: 7408 BFD5 6BC5 BF0C 361A AAE8 5D88 EEA3 B010 82D3
 From       : https://keys.datadoghq.com/DATADOG_RPM_KEY_CURRENT.public
Datadog, Inc.                                   1.4 kB/s | 1.7 kB     00:01    
Importing GPG key 0x4F09D16B:
 Userid     : "Datadog, Inc. RPM key (2024-05-15) (RPM key) <package+rpmkey@datadoghq.com>"
 Fingerprint: 2416 A377 57B1 BB02 68B3 634B 52AF C599 4F09 D16B
 From       : https://keys.datadoghq.com/DATADOG_RPM_KEY_4F09D16B.public
Datadog, Inc.                                   1.4 kB/s | 1.7 kB     00:01    
Importing GPG key 0xB01082D3:
 Userid     : "Datadog, Inc. RPM key (2023-04-20) (RPM key) <package+rpmkey@datadoghq.com>"
 Fingerprint: 7408 BFD5 6BC5 BF0C 361A AAE8 5D88 EEA3 B010 82D3
 From       : https://keys.datadoghq.com/DATADOG_RPM_KEY_B01082D3.public
Datadog, Inc.                                   2.0 kB/s | 2.4 kB     00:01    
Importing GPG key 0xFD4BF915:
 Userid     : "Datadog, Inc. RPM key (2020-09-08) <package+rpmkey@datadoghq.com>"
 Fingerprint: C655 9B69 0CA8 82F0 23BD F3F6 3F4D 1729 FD4B F915
 From       : https://keys.datadoghq.com/DATADOG_RPM_KEY_FD4BF915.public
Datadog, Inc.                                   1.3 kB/s | 1.6 kB     00:01    
Importing GPG key 0xE09422B3:
 Userid     : "Datadog, Inc <package@datadoghq.com>"
 Fingerprint: A4C0 B90D 7443 CF6E 4E8A A341 F106 8E14 E094 22B3
 From       : https://keys.datadoghq.com/DATADOG_RPM_KEY_E09422B3.public
Datadog, Inc.                                    48 MB/s |  22 MB     00:00    
Last metadata expiration check: 0:00:05 ago on Tue Oct 15 11:20:14 2024.
Dependencies resolved.
================================================================================
 Package               Architecture   Version             Repository       Size
================================================================================
Installing:
 datadog-agent         x86_64         1:7.57.2-1          datadog         264 M <br />
Transaction Summary
================================================================================
Install  1 Package <br />
Total download size: 264 M
Installed size: 264 M
Downloading Packages:
datadog-agent-7.57.2-1.x86_64.rpm                68 MB/s | 264 MB     00:03    
--------------------------------------------------------------------------------
Total                                            68 MB/s | 264 MB     00:03     
Datadog, Inc.                                    51 kB/s | 1.7 kB     00:00    
Importing GPG key 0xB01082D3:
 Userid     : "Datadog, Inc. RPM key (2023-04-20) (RPM key) <package+rpmkey@datadoghq.com>"
 Fingerprint: 7408 BFD5 6BC5 BF0C 361A AAE8 5D88 EEA3 B010 82D3
 From       : https://keys.datadoghq.com/DATADOG_RPM_KEY_CURRENT.public
Key imported successfully
Datadog, Inc.                                    53 kB/s | 1.7 kB     00:00    
Importing GPG key 0x4F09D16B:
 Userid     : "Datadog, Inc. RPM key (2024-05-15) (RPM key) <package+rpmkey@datadoghq.com>"
 Fingerprint: 2416 A377 57B1 BB02 68B3 634B 52AF C599 4F09 D16B
 From       : https://keys.datadoghq.com/DATADOG_RPM_KEY_4F09D16B.public
Key imported successfully
Datadog, Inc.                                    51 kB/s | 1.7 kB     00:00    
GPG key at https://keys.datadoghq.com/DATADOG_RPM_KEY_B01082D3.public (0xB01082D3) is already installed
Datadog, Inc.                                    71 kB/s | 2.4 kB     00:00    
Importing GPG key 0xFD4BF915:
 Userid     : "Datadog, Inc. RPM key (2020-09-08) <package+rpmkey@datadoghq.com>"
 Fingerprint: C655 9B69 0CA8 82F0 23BD F3F6 3F4D 1729 FD4B F915
 From       : https://keys.datadoghq.com/DATADOG_RPM_KEY_FD4BF915.public
Key imported successfully
Datadog, Inc.                                    51 kB/s | 1.6 kB     00:00    
Importing GPG key 0xE09422B3:
 Userid     : "Datadog, Inc <package@datadoghq.com>"
 Fingerprint: A4C0 B90D 7443 CF6E 4E8A A341 F106 8E14 E094 22B3
 From       : https://keys.datadoghq.com/DATADOG_RPM_KEY_E09422B3.public
Key imported successfully
Running transaction check
Transaction check succeeded.
Running transaction test
Transaction test succeeded.
Running transaction
  Preparing        :                                                        1/1 
  Running scriptlet: datadog-agent-1:7.57.2-1.x86_64                        1/1 
  Installing       : datadog-agent-1:7.57.2-1.x86_64                        1/1 
  Running scriptlet: datadog-agent-1:7.57.2-1.x86_64                        1/1 
Enabling service datadog-agent
Created symlink /etc/systemd/system/multi-user.target.wants/datadog-agent.service → /usr/lib/systemd/system/datadog-agent.service.
No datadog.yaml file detected, not starting the agent <br />
  Verifying        : datadog-agent-1:7.57.2-1.x86_64                        1/1  <br />
Installed:
  datadog-agent-1:7.57.2-1.x86_64  <br />
Complete! <br />
* Adding your API key to the Datadog Agent configuration: /etc/datadog-agent/datadog.yaml <br /> <br />
* Setting SITE in the Datadog Agent configuration: /etc/datadog-agent/datadog.yaml <br /> <br />
/usr/bin/systemctl
* Starting the Datadog Agent... <br />
  Your Datadog Agent is running and functioning properly.
  It will continue to run in the background and submit metrics to Datadog.
  If you ever want to stop the Datadog Agent, run: <br />
      sudo systemctl stop datadog-agent <br />
  And to run it again run: <br />
      sudo systemctl start datadog-agent <br />
[ec2-user@ip-172-31-11-247 ~]$
</pre>
</details>
<br />
<b>⌘ [Start service]</b>
<pre>[ec2-user@ip-172-31-11-247 ~]$ sudo systemctl start datadog-agent</pre><br />
<b>⌘ [Status service]</b>
<pre>[ec2-user@ip-172-31-11-247 ~]$ sudo systemctl status datadog-agent</pre>
<details><summary>Overview:</summary>
<div><img src="./gambar-petunjuk/ss_ssh_instance_datadog_003.png" alt="ss_ssh" style="display: block; margin: 0 auto;"></div>
👍🏼 <b>[Done]</b> 👍🏼
<br /><hr>
</details>
</div><br /><hr>
</details>