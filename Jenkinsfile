pipeline {

    agent 
    {
        any {
            
        }
    }
     tools {
        maven 'Maven3'
    }

    stages {

         stage('Debug') {
            steps {
                sh 'pwd'
                sh 'ls -la'
                sh 'find . -name pom.xml'
            }
        }

        stage('Build') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}
