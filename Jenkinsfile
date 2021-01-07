pipeline {
    agent none
    stages {
        stage('oi-pdv-gfn') {
            agent {
                label 'oi-pdv-gfn'
            }
            steps {
                sh 'echo "hello" >> /tmp/hello_07012021.txt'
            }
        }
        stage('oi-pdv-ocs') {
            agent {
                label 'OI-PDV-OCS02'
            }
            steps {
                sh 'echo "hello" >> /tmp/hello_07012021.txt'
            }
        }           
    }
}