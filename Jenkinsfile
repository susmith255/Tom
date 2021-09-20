
pipeline {
  agent any
    stages {
      
      stage('Preparation') {
        steps {
          echo "susmith"
        }
      }
      
      stage('Tests') {
        parallel {
          stage('Unit Tests') {
            steps {
              echo "anusha"
            }
          }
          stage('Integration Tests') {
            steps {
              echo "integration"
            }
          }
          stage('Regression Tests') {
            steps {
             echo "regression"
            }
          }
          stage('Technical checks') {
            steps {
              echo "Technical checks"
            }
          }
        }
      }
      
  }
}

