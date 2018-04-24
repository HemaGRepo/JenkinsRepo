pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        bat 'javac HelloWorld.java'
      }
    }
    stage('run') {
      steps {
        bat 'java HelloWorld'
      }
    }
    stage('print') {
      steps {
        echo 'Completed'
      }
    }
  }
}