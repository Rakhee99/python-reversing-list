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
          echo 'Test is completed'
        }
      }
      stage ('Deployment Stage'){
        steps{
          echo 'Deployment successful'
        }
      }
    }
}
