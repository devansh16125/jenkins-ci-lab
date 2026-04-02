pipeline {
    agent any

    stages {
        stage('Clone Code') {
            steps {
                git 'https://github.com/devansh16125/jenkins-ci-lab.git'
            }
        }

        stage('Run Test') {
            steps {
                sh 'python3 test.py'
            }
        }
    }
}