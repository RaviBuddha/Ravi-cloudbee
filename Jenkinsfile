pipeline {
  agent {
    label 'jdk8'
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