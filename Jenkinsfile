pipeline {
    agent { label 'i5GioBOX||jetson-nano' }
    stages {
        stage('echo command') {
            steps {
                echo 'Pipeline for Python'
            }
        }
        stage('Test on Linux') {
            steps {
                sh 'echo python helloworld.py'
            }
        }
    }
}
