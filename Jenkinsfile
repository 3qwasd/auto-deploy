pipeline {
  agent {
    docker {
      image 'maven'
      args '-p 3000:3000'
    }
    
  }
  stages {
    stage('build') {
      steps {
        sh '''cd demo-1
mvn install'''
        sh '''cd demo-1
mvn install'''
      }
    }
  }
}