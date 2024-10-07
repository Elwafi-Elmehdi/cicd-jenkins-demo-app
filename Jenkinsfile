pipeline {
  agent any
  stages {
    stage ("build") {
      steps {
        echo "Running my first Jenkins Pipeline"
        sh "./gradlew build --no-daemon"
        archiveArtifacts artifects: "dist/trainSchedule.zip"
      }
    }
  }
}
