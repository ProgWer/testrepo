pipeline {
  agent any
  stages {
    stage ('Perm') {
      steps {
      sh 'chmod ugo+x gime'
      } 
    }  
    stage('Build') {
      steps {
        sh './time'
      }
    }

  }
}
