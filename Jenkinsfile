pipeline {
    agent none 
    stages {
        stage('Build') { 
            agent {
                docker {
                    image 'python:2' 
                }
            }
            steps {
                sh 'pip install requests -t .' 
            }
        }
    }
}
