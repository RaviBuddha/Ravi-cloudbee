pipeline {
  agent {
    label 'jdk9'
  }
  stages {
    stage('say hello') {
      steps {
        echo 'say hello world'
        sh 'java -version'
      }
    }
  }
}