pipeline {
  agent any
  stages {
    stage('compile') {
      steps {
        // Compile the Java file
        bat 'javac hello.java'
      }
    }
    stage('run') {
      steps {
        // Run the compiled Java program
        bat 'java hello'
      }
    }
  }
}
