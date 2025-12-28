pipeline {
    agent any # we need to give agent name , otherwise by default jenkis server
    stages {
        stage('Build') {
            steps {
                echo "building"
            }
        }
        stage('Test') {
            steps {
               echo "testing"
            }
        }
        stage('Deploy') {
            steps {
                echo "Deploying"
            }
        }
    }
}