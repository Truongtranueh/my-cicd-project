pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/Truongtranueh/my-cicd-project.git'
            }
        }

        stage('Install Dependencies') {
            steps {
                sh 'npm install'
            }
        }

        stage('Run Unit Tests') {
            steps {
                sh 'npm test'
            }
        }

        stage('Deploy (fake)') {
            steps {
                echo 'Deploying... (this is just a placeholder)'
            }
        }
    }
}
