pipeline {
  agent any
  stages {
    stage('hi') {
      steps {
        echo 'hi'
      }
    }

    stage('test') {
      steps {
        echo 'test'
      }
    }

    stage('finish') {
      steps {
        echo 'finish'
      }
    }

  }
  environment {
    test_s = 'abc'
    test_i = '123'
  }
}