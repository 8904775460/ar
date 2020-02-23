pipeline {
    agent none 
    stages {
        stage('Build') {
           withMaven { 'maven:3-Apache Maven 3.6.3' } 
            steps {
                echo 'Hello, Maven'
                sh 'mvn clean install'
            }
        }
     }
}
