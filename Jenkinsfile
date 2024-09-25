pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                // You can add build commands here, e.g., for Maven:
                // sh 'mvn clean install'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                // Add test commands here, e.g.:
                // sh 'mvn test'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
                // Add deployment commands here
            }
        }
    }
}
