pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Build completed '
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
            echo 'running test1'
          }
        }

        stage('test2') {
          steps {
            echo 'test 2'
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