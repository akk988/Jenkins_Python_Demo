pipeline {
    agent { 
        label 'i5giobox'
    }

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
