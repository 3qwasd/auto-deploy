pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '''cd demo-1
/usr/java/apache-maven-3.5.2/bin/mvn install'''
      }
    }
  }
}