<h1>AWS Identity and Access Management (IAM) Project </h1>

<h2>Description</h2>
The core objective of this project is to gain hands-on experience with AWS Identity and access management (IAM). In this Project I learned how to create IAM Identities using AWS Console and CLI, enable ' Cross account access', and finally create ' Identity Provider' in AWS. 
<br />


<h2>Tools used</h2>

- <b>AWS</b> 
- <b>Command Prompt</b>
- <b>JumpCloud</b>

<h2>Certificate</h2>
<p align="center">
<img src="https://i.imgur.com/cEngiPB.png" height="80%" width="80%" alt="IAM certificate"/>

<h2>Project Preview:</h2>

<p align="center">
Configure AWS CLI, then access AWS account programmatically with AWS CLI: <br/>
 <br />
<img src="https://i.imgur.com/zm5hupn.png" height="80%" width="80%" alt="AWS programattic login cmd"/>
<br />
<br />
Create a user with the command “aws iam create-user --user-name [enter username]”: <br/>
 <br />
<img src="https://i.imgur.com/DXtXP2E.png" height="80%" width="80%" alt="new user cmd"/>
<br />
<br />
Create a group with the command “aws iam create-group --group-name [enter group name]”: <br/>
 <br />
<img src="https://i.imgur.com/M8Rp2O9.png" height="80%" width="80%" alt="new group cmd"/>
<br />
<br />
Add user to group with the command “aws iam add-user-to-group --group-name [enter group name] --user-name [enter username]":  <br/>
 <br />
<img src="https://i.imgur.com/oqY7sIe.png" height="80%" width="80%" alt="add user to group cmd"/>
<br />
<br />
Finally, attach a policy to the group with this command “aws iam attach-group-policy --group-name [enter group name] --policy-arn [enter policy ARN]”:  <br/>
 <br />
<img src="https://i.imgur.com/a03bGJX.png" height="80%" width="80%" alt="attach policy to group cmd"/>
<br />
<br />

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
