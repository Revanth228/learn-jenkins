pipeline {
    agent {
        label 'AGENT-1'
    }
    stages {
        stage('Build') {
            steps {
                echo 'This is Build'
            }
        }
        stage('Test') {
            steps {
               echo 'This is Test stage'
            }
        }
        stage('Deploy') {
            steps {
                echo 'This is Deploy stage'
            }
        }
    }
}