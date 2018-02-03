pipeline {
  agent any
  stages {
    stage('1') {
      parallel {
        stage('1') {
          steps {
            sh 'echo "Ciao"'
          }
        }
        stage('2') {
          steps {
            sh 'echo 2'
          }
        }
      }
    }
    stage('3') {
      steps {
        sh 'echo 3'
      }
    }
  }
}