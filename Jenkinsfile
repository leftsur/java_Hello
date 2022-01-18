pipeline {
    agent any
    tools {
        maven 'maven-3.8'
    }
    stages {
        stage('Build') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}
