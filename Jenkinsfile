pipeline {
    agent any
    stages {
        stage('File compilation') {
            steps {
                javac Hello.java
            }
        }
        stage('File execution') {
            steps {
                java Hello
            }
        }
    }
}
