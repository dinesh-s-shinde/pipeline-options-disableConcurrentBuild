pipeline {
  agent any
  options {
    disableConcurrentBuilds()
  }
  stages {
    stage('Build') {
      steps {
        echo "Hello world feom disableConcurrentBuilds"
        sleep(time: 10, unit: 'SECONDS')
      }
    }
  }
}
