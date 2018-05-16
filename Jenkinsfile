pipeline {
    agent any

    stages {
        stage('Deploy to Staging') {
            when { branch "master" }
            sh 'echo "DEPLOY"'
        }
    }
}
