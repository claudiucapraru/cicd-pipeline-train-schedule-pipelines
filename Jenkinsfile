pipeline {
  agent any
  stages {
    stage('Build'){
      steps{
        echo 'runing build automation'
        sh './gradlew buid --no-deamon'
        archiveArtifacts artifacts: "dist/trainSchedule.zip"
        }
       }
    }
  }


