pipeline {
  agent {
    label 'jdk8'
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