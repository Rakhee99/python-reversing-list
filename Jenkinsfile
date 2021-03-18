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
            bat 'test\Testcalc.py'
        }
      }
      stage ('Deployment Stage'){
        steps{
          echo 'Deployment successful'
        }
      }
    }
}
