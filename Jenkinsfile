pipeline {
    agent any
    tools {
        maven 'maven-3.10.0'
    }
    stages {
        stage('Build') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}
