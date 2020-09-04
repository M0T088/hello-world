pipeline {
    agent {
    docker {
      image 'node:lts-buster-slim'
      args '-p 8989:8989'
    }
  }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
