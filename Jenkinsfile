pipeline{
 agent any
  stages {
    stage ('My Build') {
      steps {
        echo 'Running build auyomation'
        sh './gradlew build --no-daemon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }
    }
  }
  
}
