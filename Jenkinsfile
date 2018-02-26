pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'cd demo-1'
                sh 'mvn install'
            }
        }
    }
}