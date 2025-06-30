pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'cd ./frontend
                sh 'npm install'
            }
        }
        stage('Test') { 
            steps {
                sh './jenkins/scripts/test.sh' 
            }
        }
    }
}
