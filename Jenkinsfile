pipeline {
  agent none
  stages {
    stage('tegra-demo-distro') {
      steps {
        sh '''cd tegra-demo-distro
git submodule update --init
. ./setup-env --machine jetson-xavier-nx-devkit
bitbake demo-image-base'''
      }
    }

  }
}