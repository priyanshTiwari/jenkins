/* Requires the Docker Pipeline plugin */
pipeline {
    agent { docker { image 'maven:3.9.6-eclipse-temurin-17-alpine' } }
    stages {
        stage('build') {
            environment {
                  HOME="C:/Users/Priyansh/.jenkins/workspace/first-ci/"
                }
            steps {
                sh 'mvn --version'
            }
        }
    }
}
