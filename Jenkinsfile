pipeline {
  agent any
  stages {
    stage ('Perm') {
      steps {
      sh 'chmod ugo+x time'
      } 
    }  
    stage('Build') {
      steps {
        sh './time'
      }
    }

  }
}
