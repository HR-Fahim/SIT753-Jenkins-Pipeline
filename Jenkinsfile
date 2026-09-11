pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Build the application using Maven'
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo 'Run unit and integration tests using JUnit'
            }
        }

        stage('Code Analysis') {
            steps {
                echo 'Analyse code using SonarQube'
            }
        }

        stage('Security Scan') {
            steps {
                echo 'Perform security scan using OWASP Dependency-Check'
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo 'Deploy application to AWS EC2 staging server'
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo 'Run integration tests on staging environment'
            }
        }

        stage('Deploy to Production') {
            steps {
                echo 'Deploy application to AWS EC2 production server'
            }
        }
    }
}