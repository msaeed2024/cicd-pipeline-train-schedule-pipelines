pipeline {
  agent any 
  stages {
    stage ('buid') {
      stpes {
        echo 'Running Build Automation'
        sh './gradlew build --no-deamon'
        archiveArtifacts artifacts: 'dis/trainSchedule.zip'
      }
    }
  }
}
