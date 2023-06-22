pipeline {
  agent any
  stages {
    stage('start') {
      steps {
        sh 'npm install'
      }
    }

    stage('test') {
      steps {
        sh './jenkins/script/test.sh'
      }
    }

  }
}