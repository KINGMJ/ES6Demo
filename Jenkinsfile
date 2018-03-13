pipeline {
    agent { docker 'node:6.3' }
     parameters {
        string(name: 'STATUS', defaultValue: $JIRA_ISSUE_STATUS)
    }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
            }
        }
        stage('test'){
            steps{
                echo 'Testing'
                echo '现在的状态是 ${params.STATUS}'
            }
        }
        stage('deploy'){
            steps{
                echo 'Deploying'
            }
        }
    }
}
