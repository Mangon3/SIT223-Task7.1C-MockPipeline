pipeline {
    agent any
    stages {
        stage('1. Build') {
            steps {
                echo 'Description: compiling the source code and packaging it into an executable artifact.'
                echo 'Tool: Apache Maven'
            }
        }
        stage('2. Unit and Integration Tests') {
            steps {
                echo 'Description: running automated unit tests and integration tests to verify code functionality.'
                echo 'Tool: JUnit'
            }
        }
        stage('3. Code Analysis') {
            steps {
                echo 'Description: scanning the code base for bugs, code smells, and formatting issues.'
                echo 'Tool: SonarQube'
            }
        }
        stage('4. Security Scan') {
            steps {
                echo 'Description: performing Static Application Security Testing (SAST) to identify known vulnerabilities.'
                echo 'Tool: Snyk'
            }
        }
        stage('5. Deploy to Staging') {
            steps {
                echo 'Description: pushing the built artifact to a staging server for safe testing.'
                echo 'Tool: Ansible'
            }
        }
        stage('6. Integration Tests on Staging') {
            steps {
                echo 'Description: running end-to-end tests on the staging environment.'
                echo 'Tool: Selenium'
            }
        }
        stage('7. Deploy to Production') {
            steps {
                echo 'Description: final deployment of the application to the live production server.'
                echo 'Tool: Jenkins Pipeline AWS Steps'
            }
        }
    }
}