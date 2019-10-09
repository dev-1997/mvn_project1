pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        sh '''echo test
'''
      }
    }
    stage('compile') {
      steps {
        sh 'echo compile'
      }
    }
    stage('build') {
      steps {
        build 'mvn-1'
      }
    }
  }
}