pipeline {
    agent any
    tools {
        maven 'Maven3.8.4'
    }
    stages {
        stage('Build') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}
