pipeline {
    agent any
    stages {
        stage('Stage 1') {
            steps {
                echo 'Hello world!'
                echo '3'
            }
        }
        stage('Stage 2') {
            steps {
                sh 'python3 test-python.py'
            }
        }
    }
}
