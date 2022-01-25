pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                python 'main.py'
            }
        }
        stage('Build') {
            steps {
                echo 'System is Building'
            }
        }
        stage('Deploy') {
            steps {
                echo 'System is Deploying'
            }
        }
        stage('Test') {
            steps {
                echo 'System is Testing'
            }
        }
        stage('Release') {
            steps {
                echo 'System is Releasing'
            }
        }
    }
}

