pipeline {
    agent any
    tools {
        go 'go1.14'
    }
    stages {
        stage('Build') {
            steps {
                sh 'go build'
            }
        }
    }
}
