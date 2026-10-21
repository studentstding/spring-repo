pipeline {

    agent {
      any {}
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
