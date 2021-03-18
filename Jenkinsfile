pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
               bat 'python lst.py'
            }
        }
      stage('Testing Stage'){
        steps{
            bat 'python test/Testcalc.py'
        }
      }
      stage ('Deployment Stage'){
        steps{
          echo 'Deployment successful'
        }
      }
    }
}
