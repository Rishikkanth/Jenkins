pipeline {
  agent {
    node {
      label 'workstation' 
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