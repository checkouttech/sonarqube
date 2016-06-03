



running sonar runner 

    sudo ./sonar-runner-2.4/bin/sonar-runner  -D   sonar-project.properties  -e -X

    Note : remember to run as sudo 
    To point to remote sonarqube , edit the conf/sonar-runner.properties file 

    NOTE : name of properties file should end with  XXXXX-project.properties 

    #----- Default SonarQube server
    sonar.host.url=http://192.168.150.21:9000

Example 

  direct --- 
      sudo -u jenkins  /opt/sonar-runner/bin/sonar-runner -Dsonar.host.url=http://192.168.150.21:9000/ -Dsonar.projectBaseDir=/var/lib/jenkins/jobs/JavaExample/workspace/   -Dproject.settings=sonar-javaExample.properties

     sudo -u jenkins  /opt/sonar-runner/bin/sonar-runner    -Dproject.settings=sonar-javaExample.properties








