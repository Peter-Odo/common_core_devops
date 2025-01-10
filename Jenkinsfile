pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'npm install'
                sh 'npm run build'
            }
        }
        stage('Test') {
            steps {
                sh 'npm test'
            }
        }
        stage('Deploy to Staging') {
            when {
                branch 'main'
            }
            steps {
                sh 'scp -r ./dist user@staging-server:/var/www/app'
            }
        }
    }
    post {
        success {
            echo 'Deployed to Staging!'
        }
    }
}
