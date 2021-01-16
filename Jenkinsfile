pipeline {
  agent {
    node {
      label 'slave1'
    }

  }
  stages {
    stage('hello') {
      steps {
        sh 'echo \'hello world\''
      }
    }

    stage('processing') {
      steps {
        sh 'echo \'processing ....\''
        sleep 5
        sh 'echo \'processing over ...\''
      }
    }

    stage('post') {
      steps {
        sh 'echo \'post processing ... \''
        sleep 2
        sh 'echo \'post processing over ...\''
      }
    }

  }
}