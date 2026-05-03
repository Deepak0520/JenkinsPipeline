pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Stage 1: Build'
                echo 'Building the code using Maven to compile and package the application.'
                echo 'Tool: Maven'
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo 'Stage 2: Unit and Integration Tests'
                echo 'Running unit tests to ensure the code functions as expected.'
                echo 'Running integration tests to ensure components work together.'
                echo 'Tools: JUnit (unit tests), Selenium (integration tests)'
            }
        }

        stage('Code Analysis') {
            steps {
                echo 'Stage 3: Code Analysis'
                echo 'Analysing the code to ensure it meets industry standards.'
                echo 'Tool: Checkstyle'
            }
        }

        stage('Security Scan') {
            steps {
                echo 'Stage 4: Security Scan'
                echo 'Performing a security scan to identify vulnerabilities in the code.'
                echo 'Tool: OWASP Dependency-Check'
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo 'Stage 5: Deploy to Staging'
                echo 'Deploying the application to the staging server (AWS EC2 instance).'
                echo 'Tool: AWS CLI'
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo 'Stage 6: Integration Tests on Staging'
                echo 'Running integration tests on the staging environment to ensure the application functions as expected in a production-like environment.'
                echo 'Tool: Selenium'
            }
        }

        stage('Deploy to Production') {
            steps {
                echo 'Stage 7: Deploy to Production'
                echo 'Deploying the application to the production server (AWS EC2 instance).'
                echo 'Tool: AWS CLI'
            }
        }

    }
}
