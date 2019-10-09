pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        echo 'test'
      }
    }
    stage('compile') {
      steps {
        echo 'compile'
      }
    }
    stage('build') {
      steps {
        build 'mvn-1'
      }
    }
  }
}