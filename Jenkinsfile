pipeline {
    agent {
        node {
            label 'maven2'
        }
    }
    stages {
        stage('SCM Checkout') {
            steps {
                echo 'Perform SCM Checkout'
                git 'https://github.com/Avhadrajesh/java-mvn-springbootapp'
            }
        }
        stage('Application Build') {
            steps {
                echo 'Perform Application Build'
                // Execute Maven build
                // sh 'mvn clean package'
            }
        }
        stage('Deploy to Test Environment') {
            steps {
                echo 'Perform Deployment'
                // Add deployment commands here, e.g., deploying to a server
            }
        }
    }
}
