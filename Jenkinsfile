pipeline {
  agent any
  options {
    disableConcurrentBuilds()
  }
  stages {
    stage('Build') {
      steps {
        sleep(time: 2, unit: 'MINUTES')
        echo "Hello world feom disableConcurrentBuilds"
      }
    }
  }
}
