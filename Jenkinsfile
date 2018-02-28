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
        echo 'hello world'
      }
    }
  }
}