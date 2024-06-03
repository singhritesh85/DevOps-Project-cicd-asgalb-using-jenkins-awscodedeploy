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
**Deployment Group**
![image](https://github.com/singhritesh85/DevOps-Project-cicd-asgalb-using-jenkins-awscodedeploy/assets/56765895/40471488-8274-4057-be95-a247b63ed02d)
<br><br/>
