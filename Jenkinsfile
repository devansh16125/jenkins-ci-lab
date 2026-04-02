pipeline {
    agent any

    stages {
        stage('Run Test') {
            steps {
                echo "Running test..."
                bat 'python test.py'
            }
        }
    }
}