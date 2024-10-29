# Project 2
## Industry: Healthcare
Problem Statement:
How to secure patient records online and send it privately to the intended party
Topics:
In this project, you will be working on a hospital project to send reports online and
develop a platform so the patients can access the reports via mobile and push
notifications. You will publish the report to an Amazon SNS keeping it secure and
private. Your message will be hosted on an EC2 instance within your Amazon
VPC. By publishing the messages privately, you can improve the message
delivery and receipt through Amazon SNS.
Highlights:
1. AWS CloudFormation to create a VPC
2. Connect VPC with AWS SNS
3. Publish message privately with sns

   1.	Created the CloudFormation template
           Create the Stack

![Screenshot 2024-10-29 154055](https://github.com/user-attachments/assets/adb28fc0-f833-4be0-84db-05bac6083fe8)
 
  Upload the CloudFormation Template

![Screenshot 2024-10-29 154105](https://github.com/user-attachments/assets/c8cb79c9-be1c-41f0-9d0a-3325cc472a89)

Check Next

![Screenshot 2024-10-29 154116](https://github.com/user-attachments/assets/bc3cc52b-ecd8-493b-b61d-401b3956b41c)

Enter the stack name, Key Name and check Next

![Screenshot 2024-10-29 154134](https://github.com/user-attachments/assets/95e46df0-7a9d-4ac3-accf-ed196473d8d5)
![Screenshot 2024-10-29 154146](https://github.com/user-attachments/assets/89ef99e8-a744-4c02-8532-782d4695dd2f)

Resources has created

![Screenshot 2024-10-29 154206](https://github.com/user-attachments/assets/2c6fd242-4684-4b70-85af-3804ae3a0d77)

2.	Connecting VPC with SNS
First create subscription from SNS topic 

![Screenshot 2024-10-29 154232](https://github.com/user-attachments/assets/4058e1a2-7573-4575-aedf-bfa86cd7a03e)
![Screenshot 2024-10-29 154244](https://github.com/user-attachments/assets/9543e745-faa8-44c9-a989-ce6f4a473db1)
![Screenshot 2024-10-29 154253](https://github.com/user-attachments/assets/991ab663-42c3-45a7-af4e-308051fad2ff)
![Screenshot 2024-10-29 154302](https://github.com/user-attachments/assets/9fe07cd3-f850-4a8b-845b-4106cea5e380)
![Screenshot 2024-10-29 154311](https://github.com/user-attachments/assets/12b8b4d8-9dbd-438f-a030-6589b511a1ff)

Click on “Create Subscription” and you will get confirmation E-mail Click “confirm Subscription”

![Screenshot 2024-10-29 154323](https://github.com/user-attachments/assets/7028d948-1f98-4afd-8d61-6d389492bc2e)
![Screenshot 2024-10-29 154329](https://github.com/user-attachments/assets/c5b3e8f9-4f16-43f4-be67-a374b7cacdc9)

After Confirming Create VPC endpoint

![Screenshot 2024-10-29 154414](https://github.com/user-attachments/assets/a5259ee1-03bd-424a-8345-94a1f8686510)
![Screenshot 2024-10-29 154432](https://github.com/user-attachments/assets/582c9632-623d-467f-9e10-edaed0445985)
![Screenshot 2024-10-29 154443](https://github.com/user-attachments/assets/2ab8070d-9be9-45f5-ac0a-eea8f72885c4)
![Screenshot 2024-10-29 154456](https://github.com/user-attachments/assets/7d2e10c0-73f7-4b41-8cc6-ab93b326581a)
![Screenshot 2024-10-29 154505](https://github.com/user-attachments/assets/4c81fcb6-3a2a-4bd8-8e97-27e6c5d016bc)
![Screenshot 2024-10-29 154515](https://github.com/user-attachments/assets/f98f198b-df6f-4486-8063-cc0d853b22a3)

Endpoint Created 

![Screenshot 2024-10-29 154528](https://github.com/user-attachments/assets/88469c4a-6245-4e11-9b80-572b5703a1af)

3.	Publish message privately with SNS
    Connect the Ec2 instance
 
   ![Screenshot 2024-10-29 154540](https://github.com/user-attachments/assets/91d957c2-fb51-4562-a37d-269bc46a90d1)
  	![Screenshot 2024-10-29 154632](https://github.com/user-attachments/assets/afdd1dfd-e23a-4479-aa09-367ad9ec56f3)
  	![Screenshot 2024-10-29 154647](https://github.com/user-attachments/assets/0dd9818f-4050-432f-9eff-ee18d7cc3cd5)

   # Yahh Successfully Send message

























