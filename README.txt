



running sonar runner 

    sudo ./sonar-runner-2.4/bin/sonar-runner  -D   sonar-project.properties  -e -X

    Note : remember to run as sudo 
    To point to remote sonarqube , edit the conf/sonar-runner.properties file 

    #----- Default SonarQube server
    sonar.host.url=http://192.168.150.21:9000




