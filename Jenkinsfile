pipeline {
    agent {
        node {
            label 'agent1'
        }
    }
    stages {
        stage('build app') {
            steps {
                sh 'sudo apt update'
            }
        }
        stage ('test app') {
            steps {
                sh 'sudo apt install ca-certificates curl gnupg lsb-release'
            }
        }
        stage ('test docker') {
            steps {
                sh 'docker ps'
            }
        }
    }
}
