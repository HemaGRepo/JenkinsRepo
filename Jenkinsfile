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
    stage('mail') {
      steps {
        mail(subject: 'Success', body: 'The build is successful', to: 'hema.g@capgemini.com')
      }
    }
  }
}