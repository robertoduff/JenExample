pipeline {
    agent any
    stages {
        stage('Build1') {
            steps {
                sh 'echo "successful build 1"; exit 0'
            }
        }
        stage('Build2') {
            steps {
                sh 'ls -l'
                sh './copy_file'
            }
        }
        stage('Test 2') {
            steps {
                sh 'cat rob.log'
            }
        }   
    }
}
