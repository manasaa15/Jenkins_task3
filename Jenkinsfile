pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                git 'https://github.com/your-username/Cpp-Automation.git'
            }
        }
        stage('Build') {
            steps {
                sh 'g++ -o program main.cpp'
            }
        }
        stage('Execute') {
            steps {
                sh './program'
            }
        }
    }
}
