
#### 步骤1 建立开发环境  maven3.6 jdk/jre1.8
#### 步骤2 建立beanstalk 环境 并把war文件上传到此环境
#### 步骤3 建立codebuild项目
#### 步骤4 建立codepipe项目
#### 步骤5 重新打包war文件 push到github 上看结果


##### 1. clone git repo https://github.com/xuan139/awsbeanstalk-tomcat8-cicd.git
##### 2. mvn package a new version of com.webapp.war
##### 3. goto aws beanstalk console create new environment 
##### 4. select tomcat8 platform , upload com.webapp.war to environment
##### 5. goto codepipe console
##### 6. create codebuild project
##### 7. create codepipeline project
##### 8. modify src/main/java code 
##### 9. push to repo and see result    