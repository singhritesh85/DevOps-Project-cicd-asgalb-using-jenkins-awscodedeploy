# DevOps-Project-cicd-asgalb-using-jenkins-awscodedeploy
![image](https://github.com/singhritesh85/DevOps-Project-cicd-asgalb-using-jenkins-awscodedeploy/assets/56765895/7f1e8c68-f6fc-426b-9a48-24aa6f7a8ac6)
<br><br/>
End-to-end Architecture diagram is as shown in the screenshot attached above. For this demonstration source code is present in GitHub Repository and Jenkins uses this source code. CI/CD pipeline has been created using Jenkins Freestyle Job.
<br><br/>
There are four required plugins for Jenkins to achieved this as listed below.
```
1.	Environment Injector
2.	SonarQube Scanner
3.	Nexus Artifact Upload
4.	AWS CodeDeploy
```
After installation of these four plugin configure SonarQube from Manage Jenkins > Systems as show in the screenshot below.
<br><br/>
![image](https://github.com/singhritesh85/DevOps-Project-cicd-asgalb-using-jenkins-awscodedeploy/assets/56765895/781905d0-dbed-4979-bb9c-0ccd061cdd9f)
![image](https://github.com/singhritesh85/DevOps-Project-cicd-asgalb-using-jenkins-awscodedeploy/assets/56765895/1d8b6cc0-b344-416b-81b1-15a5b3f8c2ba)
<br><br/>
Webhook has been created for SonarQube as shown in the screenshot below.
<br><br/>
![image](https://github.com/singhritesh85/DevOps-Project-cicd-asgalb-using-jenkins-awscodedeploy/assets/56765895/776a2af7-9cbe-475a-b8a9-17f6bb7f17d6)
<br><br/>
Create Application, Deployment Group and an IAM Policy which is required by Jenkins for AWS CodeDeploy.
<br><br/>
**IAM POlicy**
![image](https://github.com/singhritesh85/DevOps-Project-cicd-asgalb-using-jenkins-awscodedeploy/assets/56765895/b60a37c2-3cf5-4475-a6e4-7a203fb6a07e)
**Application for AWS CodeDeploy**
![image](https://github.com/singhritesh85/DevOps-Project-cicd-asgalb-using-jenkins-awscodedeploy/assets/56765895/ae1f8381-d53a-406f-8a77-b353b7b665c8)
**Deployment Group for AWS CodeDeploy**
![image](https://github.com/singhritesh85/DevOps-Project-cicd-asgalb-using-jenkins-awscodedeploy/assets/56765895/40471488-8274-4057-be95-a247b63ed02d)
<br><br/>
**Creation of FreeStyle Jenkins Job**
<br><br/>
![image](https://github.com/singhritesh85/DevOps-Project-cicd-asgalb-using-jenkins-awscodedeploy/assets/56765895/a7d87b83-57de-41f4-ae45-bca5374f80ae)
![image](https://github.com/singhritesh85/DevOps-Project-cicd-asgalb-using-jenkins-awscodedeploy/assets/56765895/b44c3ed4-7dd5-44e9-94cc-ba6fc68519e3)
![image](https://github.com/singhritesh85/DevOps-Project-cicd-asgalb-using-jenkins-awscodedeploy/assets/56765895/365377f2-8d5e-4149-9406-a2e800d67fa3)
![image](https://github.com/singhritesh85/DevOps-Project-cicd-asgalb-using-jenkins-awscodedeploy/assets/56765895/cd7eecf7-a29c-43fb-92d9-ef5321464537)
![image](https://github.com/singhritesh85/DevOps-Project-cicd-asgalb-using-jenkins-awscodedeploy/assets/56765895/c89dd6a8-0b5c-436e-8006-192c0d6155d9)
![image](https://github.com/singhritesh85/DevOps-Project-cicd-asgalb-using-jenkins-awscodedeploy/assets/56765895/088bae04-678f-43af-89d5-502aa184fe32)
![image](https://github.com/singhritesh85/DevOps-Project-cicd-asgalb-using-jenkins-awscodedeploy/assets/56765895/2cc7e787-cf70-4003-a1e2-06d4151b8306)
![image](https://github.com/singhritesh85/DevOps-Project-cicd-asgalb-using-jenkins-awscodedeploy/assets/56765895/2c9ea988-be2e-4edb-a986-29b4374bc6c2)
![image](https://github.com/singhritesh85/DevOps-Project-cicd-asgalb-using-jenkins-awscodedeploy/assets/56765895/ebf62259-ff3a-4026-a69d-34968b88f800)
![image](https://github.com/singhritesh85/DevOps-Project-cicd-asgalb-using-jenkins-awscodedeploy/assets/56765895/29bbb9f3-c291-4559-9e53-7c6a144c6234)
