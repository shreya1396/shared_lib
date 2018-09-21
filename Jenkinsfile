pipeline {
  agent any
  stages {
    stage('Install ') {
      steps {
        echo 'To install dependencies'
        sh 'apt-get update'
        sh 'apt-get install vim'
      }
    }
    stage('Build') {
      steps {
        echo 'make build'
      }
    }
    stage('Test') {
      steps {
        echo 'to test'
      }
    }
  }
}
