pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Build step Success'
      }
    }
    stage('Package') {
      parallel {
        stage('Package') {
          steps {
            echo 'success'
          }
        }
        stage('Package from good tar') {
          steps {
            echo 'success'
          }
        }
        stage('Report Missing commits') {
          steps {
            echo 'success'
          }
        }
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deploy'
      }
    }
  }
}