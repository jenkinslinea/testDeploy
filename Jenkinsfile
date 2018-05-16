pipeline {
    agent any
    stages {
        stage('Deploy') {
            when { tag "v*" }
            steps {
                echo 'Deploying'
            }
        }
    }
}
