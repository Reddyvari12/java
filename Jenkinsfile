pipeline {
  agent none
  stages {
    stage('develop') {
      steps {
        sh 'echo "hello1"'
      }
    }

    stage('test') {
      steps {
        sh 'echo "hello2"'
      }
    }

    stage('prod') {
      steps {
        sh 'echo "hello2"'
      }
    }

  }
  environment {
    simple = ''
  }
}