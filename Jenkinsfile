pipeline {
  agent {
    dockerfile {
      filename 'Dockerfile'
    }
    
  }
  stages {
    stage('') {
      steps {
        sh 'docker build -t go-hello .'
      }
    }
  }
}