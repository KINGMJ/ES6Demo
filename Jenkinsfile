pipeline {
    agent { docker 'node:6.3' }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
            }
        }
        stage('test'){
            steps{
                echo 'Testing'
            }
        }
        stage('deploy'){
            steps{
                echo 'Deploying'
            }
        }
    }
}
