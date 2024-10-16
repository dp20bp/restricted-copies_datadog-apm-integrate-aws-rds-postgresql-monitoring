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