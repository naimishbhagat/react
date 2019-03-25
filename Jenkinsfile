pipeline {
    agent { docker { image 'node:6.3' } }
    stages {
        stage('master') {
            steps {
                sh 'npm --version'
            }
        }
    }
}