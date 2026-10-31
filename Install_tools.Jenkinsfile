
pipeline {
    agent any

    stages {
        stage('Python Version') {
            steps {
                sh "python3 --version"
            }
        }

        stage('Docker Version') {
            steps {
                sh "docker -v"
            }
        }

        stage('Install Make') {
            steps {
                sh "make --version"
            }
        }
    }
}
