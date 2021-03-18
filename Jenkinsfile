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
            tool name: 'python-R', type: 'jenkins.plugins.shiningpanda.tools.PythonInstallation'
          bat '*/test/Testcalc.py'
          echo 'test successful'  
        }
      }
      stage ('Deployment Stage'){
        steps{
          echo 'Deployment successful'
        }
      }
    }
}
