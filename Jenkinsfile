pipeline {
  agent {
    label 'jdk9'
  }
  stages {
    stage('hello') {
      steps {
        echo 'Hello World'
        sh 'java -version'
      }
    }
  }
}