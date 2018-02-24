pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'ls -l'
      }
    }
    stage('Test') {
      steps {
        sh 'ls -l'
      }
    }
    stage('Staging') {
      steps {
        input 'Deploy?'
        sh 'ls -l'
      }
    }
    stage('Production') {
      steps {
        input 'Deploy?'
      }
    }
  }
}