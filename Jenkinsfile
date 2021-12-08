pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
        echo 'Rinning Build Automation'
        sh './gradlew build --no-daemon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      
      }
    }
  }
}
