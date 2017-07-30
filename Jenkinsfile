pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        dockerNode(image: 'node:6.3') {
          sh 'npm --version'
        }
        
      }
    }
  }
}