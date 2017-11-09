pipeline {
  agent any
  stages {
    stage('ga') {
      parallel {
        stage('A') {
          steps {
            sh '''echo "Hello World"
'''
          }
        }
        stage('B') {
          steps {
            sh 'echo bla'
          }
        }
      }
    }
  }
}