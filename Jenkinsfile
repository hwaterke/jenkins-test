pipeline {
  agent {
    docker {
      image 'node:9'
    }

  }
  stages {
    stage('stage1') {
      steps {
        sh 'echo "Hello World"'
        sh 'node -v'
      }
    }
  }
}