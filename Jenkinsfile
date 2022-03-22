pipeline {
    stages {
        stage('echo command') {
            steps {
                echo 'Pipeline for Python'
            }
        }
        stage('Test on Linux') {
            agent { 
                label 'i5GioBOX'
            }
            steps {
                unstash 'app' 
                sh 'echo python helloworld.py'
            }
        }
    }
}
