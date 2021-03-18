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
            sh 'python Testcalc.py'
        }
      }
      stage ('Deployment Stage'){
        steps{
          echo 'Deployment successful'
        }
      }
    }
}
