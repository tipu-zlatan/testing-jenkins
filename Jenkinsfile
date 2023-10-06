pipeline {
    agent any
    stages {
        stage('Stage 1') {
            steps {
                echo 'Create Container Image..'
        
                script {
                        echo 'Hello world!'
                        echo '3'
                            }
                        }
                }
            
        
        stage('Stage 2') {
            steps {
                echo 'pyhton thing'
                script {
                        sh 'python3 test-python.py'
            }
        }
    }
}
}
