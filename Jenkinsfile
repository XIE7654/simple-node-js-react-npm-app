pipeline {
    agent none
    stages {
        stage('Build') {
            agent {
                docker {
                    image 'node:10.24.0'
                    args '-p 3000:3000'
                }
            }
        }

        stage('node-Build') {
            steps {
                sh 'npm install'
            }
        }
    }
}
