pipeline {
    agent {
        docker { image 'python:3.8' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'python --version'
            }
        }
    }
}
