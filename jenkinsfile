
pipeline {
  agent any
    stages {
      
      stage('Preparation') {
        steps {
          // Cleanup, Environment setup, etc.
        }
      }
      
      stage('Tests') {
        parallel {
          stage('Unit Tests') {
            steps {
              // Invoke unit tests
            }
          }
          stage('Integration Tests') {
            steps {
              // Invoke integration tests
            }
          }
          stage('Regression Tests') {
            steps {
             // Invoke regression tests
            }
          }
          stage('Technical checks') {
            steps {
              // Invoke Technical checks
            }
          }
        }
      }
      
  }
}

