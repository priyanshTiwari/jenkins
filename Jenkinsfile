/* Requires the Docker Pipeline plugin */
pipeline {
    agent { docker { image 'ubuntu:latest' } }
    stages {
        stage('build') {
            steps {
                sh 'java --version'
            }
        }
    }
}
