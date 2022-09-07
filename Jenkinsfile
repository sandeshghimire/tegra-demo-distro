pipeline {
  agent none
  stages {
    stage('tegra-demo-distro') {
      steps {
        sh '''git submodule update --init
. ./setup-env --machine jetson-xavier-nx-devkit
bitbake demo-image-base'''
      }
    }

    stage('') {
      steps {
        sh '''git submodule update --init
. ./setup-env --machine jetson-xavier-nx-devkit
bitbake demo-image-base'''
      }
    }

  }
}