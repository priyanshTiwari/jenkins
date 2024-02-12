/* Requires the Docker Pipeline plugin */
pipeline {
    agent { docker { image 'ubuntu:latest' } }
    stages {
        stage('build') {
            environment{
                HOME="//Users/Priyansh/.jenkins/workspace/first-ci/"
            }
            steps {
                sh 'java --version'
            }
        }
    }
}
