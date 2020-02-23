pipeline {
    agent none 
    stages {
        stage('Build') {
            agent { 'maven:3-Apache Maven 3.6.3' } 
            steps {
                echo 'Hello, Maven'
                sh 'mvn --version'
            }
        }
     }
}
