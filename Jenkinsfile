pipeline {
    agent { label 'Agent_Docker' }

    stages {
        stage('Python in container') {
            agent {
                docker {
                    image 'python:3.11'
                }
            }
            steps {
                sh 'python --version'
            }
        }
    }
}
