pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                sh """
                docker build -t hello_World .
                """
            }
        }
        stage("run") {
            steps {
                sh """
                docker run --rm hello_World
                """
            }
        }
    }
}

