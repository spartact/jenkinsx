pipeline {
  agent {
    docker {
      image 'jdeathe/centos-ssh:centos-6'
      args '--name cccccc --rm -p 2022:22'
    }
    
  }
  stages {
    stage('step1') {
      steps {
        sh 'ls -l'
        sh 'hostname'
      }
    }
  }
}