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
                echo 'build app...'
                sh 'cd ./frontend'
                sh 'npm install'
            }
        }
    }
}
