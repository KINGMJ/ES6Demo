pipeline {
    agent {docker 'node:6.3'}
    stages {
        stage('build') {
            steps {
                sh 'echo "hello world"'
                sh 'npm --version'
            }
        }
    }
}
