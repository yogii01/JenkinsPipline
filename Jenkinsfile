pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'python -m py_compile sources/main.py'
            }
        }
    }
}

