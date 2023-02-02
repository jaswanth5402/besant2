pipeline {
  agent any
  stages {
    stage('download') {
      steps {
        nodejs('my-node') {
          sh 'nom install'
        }

      }
    }

    stage('build ') {
      steps {
        nodejs('my-node') {
          sh 'ng build'
        }

      }
    }

  }
}