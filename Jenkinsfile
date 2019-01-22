pipeline {
  agent any
  stages {
    stage ('Build') {
      echo 'Running build automation'
      sh './gradelw build --no-deamon'
      archiveArtifatcs artifatcs: 'dist/trainSchedule.zip'
      
    }

}
}
