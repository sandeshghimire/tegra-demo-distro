pipeline {
  agent any
  stages {
    stage('clone') {
      steps {
        sh '. ./setup-env  --machine jetson-xavier-nx-devkit --distro tegrademo  build-testdistro'  
      }
    }

  }
}