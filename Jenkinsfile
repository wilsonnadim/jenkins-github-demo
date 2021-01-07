pipeline {
    agent any
    stages {
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