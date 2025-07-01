pipeline {
    agent none
    stages {
        stage('Build') {
            agent {
                docker {
                    image 'stuffy3834/nodejs'
                }
            }
            steps {
                dir('./frontend') {
                    echo 'build app...'
                    sh 'npm install'
                }
            }
        }
    }
}
