pipeline {
  agent {
    node {
      label 'Jenkins_workstation' 
     }
   }
   stages {

    stage('stage1') {
      steps {
        sh 'echo Jenkins pipeline builted'
      }
    }

        stage('stage2') {
      steps {
        sh 'echo Jenkins pipeline stage2'
      }
    }
  }
}