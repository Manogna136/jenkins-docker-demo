pipeline {
    agent any

    stages {
        stage('Ckeckout') {
            steps {
                git 'https://github.com/Manogna136/jenkins-docker-demo.git'
            }
        }
        stage('Install') {
            steps {
                sh 'npm install'
            }
        }
        stage('Test') {
            steps {
                echo 'Running Tests....'
            }
        }
    }
}