pipeline {
    agent any
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