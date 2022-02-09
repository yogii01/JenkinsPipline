pipeline {
    agent {label 'Slave1'}
    
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
        agent {label 'Slave1'}
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
