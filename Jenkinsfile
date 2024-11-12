pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        bat 'python --version' // Checks Python version
      }
    }
    stage('hello') {
      steps {
        bat 'python p1.py' 
      }
    }
  }
}
