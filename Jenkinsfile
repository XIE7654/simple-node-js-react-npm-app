pipeline {
    agent {
        docker {
            image 'node:10.24.0'
            args '-p 3000:3000'
        }
    }
    stages {
        stage('Build') {
            steps {
                sh 'npm install'
            }
        }
    }
}