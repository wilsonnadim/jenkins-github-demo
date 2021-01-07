pipeline {
    agent any

    stages {
        stage('Comando no Windows22') {
            agent {
                label 'windows'
            }
            steps {
                bat 'echo %COMPUTERNAME%'
                bat 'ipconfig'
            }
        }
        stage('Comando no Linux') {
            agent {
                label 'linux'
            }
            steps {
                sh 'echo $HOSTNAME'
                sh 'ifconfig'
            }

        }
    }
}