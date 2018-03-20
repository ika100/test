pipeline {
  agent any
  stages {
    stage('say hello') {
      steps {
        echo 'hello'
      }
    }
    stage('say good buy') {
      parallel {
        stage('say good buy') {
          steps {
            echo 'good by'
          }
        }
        stage('not valid') {
          steps {
            echo 'not valid'
          }
        }
      }
    }
    stage('test') {
      steps {
        echo 'test'
      }
    }
  }
}