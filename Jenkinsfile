pipeline {
  agent any 
  stages {
    stage ('build') {
      steps {
        echo 'Running Build Automation'
        sh './gradlew build --no-deamon'
        archiveArtifacts artifacts: 'dis/trainSchedule.zip'
      }
    }
  }
}
