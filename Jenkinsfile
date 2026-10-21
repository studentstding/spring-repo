pipeline {

    agent any

    tools {
        maven 'Maven3'
    }

    stages {

stage('info') {
    steps {
        sh 'mvn --version'
    }
}
        
        stage('Build') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}
