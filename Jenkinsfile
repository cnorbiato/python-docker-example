pipeline {
  agent {
    dockerfile {
      filename 'dockerfile'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'docker build -t cnorbiato/python-docker-example'
      }
    }

  }
}