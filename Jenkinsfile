pipeline {
    agent { docker 'node:6.5' }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
                sh 'node ./ci.js'
            }
        }
    }
}
