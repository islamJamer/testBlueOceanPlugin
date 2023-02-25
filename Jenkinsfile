pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'test'
      }
    }

    stage('Test stages') {
      parallel {
        stage('Test stages') {
          steps {
            echo 'test'
          }
        }

        stage('test 1') {
          steps {
            echo 'running test11'
          }
        }

      }
    }

    stage('deploy') {
      steps {
        echo 'completed '
      }
    }

  }
}