pipeline {
    agent none
    stages {
        stage('Build') {
            agent {
                docker {
                    image 'stuffy3834/nodjs-v1'
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
