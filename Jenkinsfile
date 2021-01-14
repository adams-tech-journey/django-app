// pipeline {
//     agent any
//     environment {
//         COMPOSE_PROJECT_NAME = "${env.JOB_NAME}-${env.BUILD_ID}"
//     }
//     stages {
//         stage('Setup') {
//             steps {
//                 sh 'docker-compose --version'
//     }
//     post {
//         always {
//             sh "docker-compose down -v"
//         }
//     }
// }

 pipeline {
    agent { dockerfile true }
    stages {
        stage('Test') {
            steps {
                sh 'python --version'
            }
        }
    }
}