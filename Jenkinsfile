pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                // TODO: Add the build step
                sh './gradlew assemble'
            }
        }
        stage('Test') {
            steps {
                // TODO: Add the test step
                sh './gradlew test'
            }
        }
        stage('Deploy') {
            steps {
                sh 'deploy-to-production.sh'
            }
        }
    }
}