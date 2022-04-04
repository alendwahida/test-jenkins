pipeline {
    agent {
        node {
            label 'agent1'
        }
    }
    stages {
        stage('build app') {
            steps {
                sh 'apt update'
            }
        }
        stage ('test app') {
            steps {
                sh 'apt install ca-certificates curl gnupg lsb-release'
            }
        }
    }
}
