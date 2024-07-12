# hello-tomcat

```
docker build -t hello-tomcat .
docker run -p 8000:8080 hello-tomcat
http://localhost:8000/demo
```

```
Install-Module -Name AWS.Tools.Installer -Force
Install-AWSToolsModule AWS.Tools.EC2,AWS.Tools.S3 -CleanUp
Install-AWSToolsModule AWS.Tools.ECR
Set-AWSCredential -AccessKey akey -SecretKey skey -StoreAs name
Set-AWSCredential -ProfileName name
aws configure
```

```
 msiexec.exe /i https://awscli.amazonaws.com/AWSCLIV2.msi
```
