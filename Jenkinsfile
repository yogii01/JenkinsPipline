pipeline {
    agent {label 'Slave'}
    
    stages {
        stage('Test') {
            steps {
                echo 'Testing'
            }
        }
        stage('Release') {
            steps {
                echo 'Releasing'
            }
        }   
        stage('Test1') {
        agent {label 'Slave'}
            steps {
                echo 'Testing'
            }
        }
        stage('Release1') {
            steps {
                echo 'Releasing'
            }
        }
    }    
}
