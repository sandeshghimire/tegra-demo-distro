pipeline {
  agent any
  stages {
    stage('clone') {
      steps {
        sh '. ./setup-env --machine jetson-xavier-nx-devkit-emmc --distro tegrademo jetson-xavier-nx-devkit-emmc jetson-xavier-nx-devkit-emmc'  
      }
    }

  }
}