pipeline {
    agent any

    stages {
        stage('echo command') {
            steps {
                echo 'Pipeline for Python'
            }
        }
        stage('Build') {
            steps {
                echo '\kafka\examples\ docker-compose up'
            }
        }
    }
}
