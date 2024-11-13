pipeline {
    agent any

    stages {
        stage('SCM_Checkout') {
            steps {
                echo 'Perform SCM Checkout'
                git 'https://github.com/Avhadrajesh/java-mvn-springbootapp'
            }
        }
        stage('Application Build') {
            steps {
                echo 'Perform Application Build'
            }
        }
        stage('Deploy to Test Environment') {
            steps {
                echo 'Perform Deployment'
            }
        }
    }
}
