pipeline {
    agent any

    stages {

        stage('Clone Repository') {
            steps {
                git branch: 'main', url: 'https://github.com/lalitha0502/JENKINS.git'
            }
        }

        stage('Start') {
            steps {
                echo 'Starting Jenkins Build'
            }
        }

        stage('Student Details') {
            steps {
                echo 'Name: Srilalitha'
                echo 'Roll Number: 2023BCS0214'
            }
        }

        stage('Build') {
            steps {
                echo 'Building the sample project from GitHub repository'
            }
        }

        stage('Finish') {
            steps {
                echo 'Build completed successfully'
            }
        }
    }
}
