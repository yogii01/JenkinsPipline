pipeline {
    agent { docker { image 'python:3.9.7-alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
    }
}
