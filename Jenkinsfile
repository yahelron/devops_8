pipeline {
agent any
    stages {
        stage('checkout') {
            steps {
                git 'https://github.com/yahelron/devops_8.git'
            }
        }
        stage('build') {
            steps {
                bat 'first.py'
            }
        }
    }
}
