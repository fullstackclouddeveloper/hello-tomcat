# hello-tomcat
```
git clone https://github.com/fullstackclouddeveloper/hello-tomcat.git
```

```
docker build -t hello-tomcat .
docker run -p 8080:8080 hello-tomcat
http://localhost:8080/demo
```

```
msiexec.exe /i https://awscli.amazonaws.com/AWSCLIV2.msi
aws configure
```

```
aws ecr get-login-password --region us-east-2 | docker login --username AWS --password-stdin 482464276980.dkr.ecr.us-east-2.amazonaws.com
docker tag hello-tomcat:latest 482464276980.dkr.ecr.us-east-2.amazonaws.com/hello-tomcat:latest
docker push 482464276980.dkr.ecr.us-east-2.amazonaws.com/hello-tomcat:latest
```

Probably not this
```
Install-Module -Name AWS.Tools.Installer -Force
Install-AWSToolsModule AWS.Tools.EC2,AWS.Tools.S3 -CleanUp
Install-AWSToolsModule AWS.Tools.ECR
Set-AWSCredential -AccessKey akey -SecretKey skey -StoreAs name
Set-AWSCredential -ProfileName name
aws configure
```
