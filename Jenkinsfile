pipeline{
 agent any
  stages{
    stage('build'){
      steps{
        echo 'running build automation'
        sh './gradlewbuild --no--daemon'
        archiveArtifacts artifacts: '/dist/trainSchedule.zip'
        
      }
    }
  }
}
