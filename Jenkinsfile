pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        bat 'git clone https://github.com/balajireddy8898/spring4-mvc-example.git'
      }
    }
    stage('build') {
      steps {
        bat 'mvn clean install'
      }
    }
  }
}