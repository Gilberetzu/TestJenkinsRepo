pipeline {
    agent any
    stages {
        stage('test') {
            steps {
                bat 'npm --version'
                bat 'npm test'
                bat 'npm --version'
            }
        }
    }
}