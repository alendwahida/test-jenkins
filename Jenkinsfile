pipeline {
    agent {
        node {
            label 'agent1'
        }
    }
    stages {
        stage('docker Version') {
            steps {
                sh 'docker version'
            }
        }
        stage ('pull Github') {
            steps {
                sh 'git --version'
            }
        }
        stage ('docker Build') {
            steps {
                sh 'docker ps'
            }
        }
    }
}
