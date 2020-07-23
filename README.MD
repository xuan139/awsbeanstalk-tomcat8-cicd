1.clone git repo https://github.com/xuan139/awsbeanstalk-tomcat8-cicd.git
2. mvn package a new version of com.webapp.war
3. goto aws beanstalk console create new environment 
4. select tomcat8 platform , upload com.webapp.war to environment
5. goto codepipe console
6. create codebuild project
7. create codepipeline project
8. modify src/main/java code 
9. push to repo and see result    