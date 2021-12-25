pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'python time.py'
      }
    }
    stage('Test') {
      parallel {
        stage('Test') {
          steps {
            sh 'echo \'Testing..\''
          }
        }

        stage('Deploy') {
          steps {
            sh 'echo \'Deploying....\''
          }
        }

      }
    }

  }
}
