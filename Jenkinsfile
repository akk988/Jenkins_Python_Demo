pipeline {
    agent none
    stages {
        stage('echo command') {
            steps {
                echo 'Pipeline for Python'
            }
        }
        stage('Test on Linux') {
            agent { 
                label 'i5giobox'
            }
            steps {
                unstash 'app' 
                sh 'echo python helloworld.py'
            }
        }
    }
}
