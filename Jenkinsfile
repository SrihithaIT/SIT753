pipeline {
    agent any

    stages {
        stage("Build") {
            steps {
                bat 'echo Using Maven to build and package the application SIT753'
            }
        }

        stage("Unit and Integration Tests") {
            steps {
                bat 'echo Using JUnit to run unit and integration tests SIT753'
            }
        }

        stage("Code Analysis") {
            steps {
                bat 'echo Using SonarQube to perform static code analysis and ensure code quality SIT753'
            }
        }

        stage("Security Scan") {
            steps {
                bat 'echo Using Snyk to scan the codebase for known vulnerabilities SIT753'
            }
        }

        stage("Deploy to Staging") {
            steps {
                bat 'echo Deploying the application to a staging server SIT753(AWS EC2 instance)'
            }
        }

        stage("Integration Tests on Staging") {
            steps {
                bat 'echo Using Selenium to perform integration testing on the staging environment SIT753'
            }
        }

        stage("Deploy to Production") {
            steps {
                bat 'echo Deploying the application to the production server SIT753(AWS EC2 instance)'
            }
        }
    }
}
