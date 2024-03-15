pipeline {
  agent any
  stages {
    stage('Init in repo7') {
      steps {
        echo "Hello from Jenkinsfile of repo7"
      }
    }
    /*stage("build") {
      steps {
        sh 'docker ps'
        sh """
          docker build -t hello_there .
        """
      }
    }
    stage("run") {
      steps {
        sh """
          docker run --rm hello_there
        """
      }
    }*/
  }
}
