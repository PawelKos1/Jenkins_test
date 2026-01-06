pipeline {
    agent { docker { image 'python:3.14.2-alphine3.23' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
    }
}
