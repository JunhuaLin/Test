pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
                sh 'node ./ci.js'
            }
        }
    }
}
