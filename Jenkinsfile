pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                git 'https://github.com/saish-coditas/Git-Demo1.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building...'
                // Add build commands here, e.g., mvn clean install
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                // Add test commands here, e.g., mvn test
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
                // Add deployment commands here, e.g., scp target/*.jar user@server:/path
            }
        }
    }
}
