pipeline {
    agent any
    tools {
        maven 'maven-3.10'
    }
    stages {
        stage('Build') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}
