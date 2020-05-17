pipeline {
  agent any
  stages {
    stage('Get HostName') {
      steps {
        sh 'echo $HOSTNAME'
        echo 'This is my System hostname'
      }
    }

    stage('Java Hello Check') {
      steps {
        sh 'java HelloWorld'
      }
    }

  }
}