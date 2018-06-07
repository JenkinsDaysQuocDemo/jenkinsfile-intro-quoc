pipeline {
  agent {
    label 'jdk8'
  }
  stages {
    stage('hello') {
      steps {
        echo "Hello ${MY_NAME}"
        sh 'java -version'
        echo "${TEST_USER_USR}"
        echo "${TEST_USER_PSW}"
      }
    }
  }
  environment {
    MY_NAME = 'Quoc'
    TEST_USER = credentials('test-user')
  }
}