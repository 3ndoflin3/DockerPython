pipeline {
  agent {
    dockerfile {
      filename 'Dockerfile'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'python3 prueba.py'
      }
    }

  }
}
