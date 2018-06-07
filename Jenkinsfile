pipeline {
  agent {
    label 'jdk8'
  }
  stages {
    stage('hello') {
      steps {
        echo "Hello ${MY_NAME}"
        sh 'java -version'
      }
    }
  }
  environment {
    MY_NAME = 'Quoc'
  }
}