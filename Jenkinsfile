/* Requires the Docker Pipeline plugin */
pipeline {
    agent { docker { image 'node:18.16.0-alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'node --version'
                sh 'uname -a'
            }
        }
        stage('deploy') {
            steps {
                sh 'echo "Deployment Step"'
            }
        }
    }
}