pipeline {
  agent any
  stages {
    stage('Buid'){
      steps{
        echo 'runing build automation'
        sh './gradlew buid --no-deamon'
        archiveArtifacts artifacts: "dist/trainSchedule.zip"
        }
       }
    }
  }


