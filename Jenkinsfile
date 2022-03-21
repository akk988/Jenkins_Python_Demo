pipeline {
    agent { label 'i5giobox || jetson-nano' }

    stages {
        stage('echo command') {
            steps {
                echo 'Pipeline for Python'
            }
        }
        stage('Build') {
            steps {
                echo 'python helloworld.py'
            }
        }
    }
}
