pipeline {
    agent any
    stages {
        stage('Comando no Linux') {
            agent {
                label 'OI-PDV-OCS02'
            }
            steps {
                sh 'echo $HOSTNAME'
                sh 'ifconfig'
            }
        }
    }
}