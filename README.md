Extract the pawandeep_sp_angular_test.zip

steps to execute the project

1.Requirement:

1.apache maven 3. x version(mvn project)
2.tomcat server 7.x version(to up the war)

2.Commands to excute the war:

1. mvn clean install (to build the war)

3.Script to copy the war to the webapp folder

del "C:\Users\user\Downloads\Tomcat\apache-tomcat-7.0.37-windows-x86\apache-tomcat-7.0.37\webapps\SampleProject.war"

rmdir "C:\Users\user\Downloads\Tomcat\apache-tomcat-7.0.37-windows-x86\apache-tomcat-7.0.37\webapps\SampleProject" /s /q

copy "C:\Users\user\Downloads\Eclipse\Workspaces\Wokspace 2\SampleProject\target\SampleProject.war" "C:\Users\user\Downloads\Tomcat\apache-tomcat-7.0.37-windows-x86\apache-tomcat-7.0.37\webapps"

4.The war is up ready to execute.# AngularJS
EnukeAssignmentProject
