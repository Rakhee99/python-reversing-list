pipeline {
    agent any

    stages {
        stage('Compiling-stage') {
            steps {
               bat 'lst.py'
            }
        }
      stage('testing-Stage'){
        steps{
            bat test/Testcalc.py
        }
      }
      stage ('Deployment-Stage'){
        steps{
          echo 'Deployment successful'
        }
      }
    }
}
