pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
               bat 'lst.py'
            }
        }
      stage('Testing Stage'){
        steps{
            bat 'Testcalc.py'
        }
      }
      stage ('Deployment Stage'){
        steps{
          echo 'Deployment successful'
        }
      }
    }
}
