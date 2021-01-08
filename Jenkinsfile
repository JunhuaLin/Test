pipeline {
    agent { docker 'node:14.15.0' }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
                sh 'node ./ci.js'
            }
        }
    }
}
