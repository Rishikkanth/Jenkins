pipeline {
  agent {
    node {
      label 'Jenkins_workstation' 
     }
   }

   environments {
     CREDS = credentials('CENTOS')
   }

   stages {

    stage('stage1') {
      steps {
        sh 'echo Jenkins pipeline builted, CREDS = $CREDS'
      }
    }

        stage('stage2') {
      steps {
        sh 'echo Jenkins pipeline stage2'
      }
    }
  }
}