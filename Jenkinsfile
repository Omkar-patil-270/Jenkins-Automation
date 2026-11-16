pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Fetching source code from GitHub'
            }
        }

        stage('Build') {
            steps {
                echo 'Building Java Application'
                bat 'javac Hello.java'
            }
        }

        stage('Run') {
            steps {
                echo 'Running Java Application'
                bat 'java Hello'
            }
        }

        stage('Complete') {
            steps {
                echo 'Jenkins Automation Completed Successfully!'
            }
        }
    }
}