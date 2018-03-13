pipeline {
    agent { docker 'node:6.3' }
     environment{JIRA_ISSUE_STATUS=	credentials('JIRA_ISSUE_STATUS')}
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
            }
        }
        stage('test'){
            steps{
                echo '输出环境变量'
                sh 'printenv'
            }
        }
        stage('deploy'){
            steps{
                echo 'Deploying'
            }
        }
    }
}
