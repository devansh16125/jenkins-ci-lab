pipeline {
    agent any

    stages {
        stage('Build & Test') {
            steps {
                echo 'Running CI Pipeline...'
                sh 'python3 test.py'
            }
        }
    }
}
