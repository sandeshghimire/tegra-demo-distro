pipeline {
  agent none
  stages {
    stage('tegra-demo-distro') {
      steps {
        sh '''pwd ; git submodule update --init ;
. ./setup-env --machine jetson-xavier-nx-devkit ;
bitbake demo-image-base ;'''
      }
    }
  }
}