pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'build completed'
      }
    }

    stage('Test Stage') {
      parallel {
        stage('Test1') {
          steps {
            echo 'running test1'
          }
        }

        stage('Test2') {
          steps {
            echo 'running test2'
          }
        }

      }
    }

    stage('Deploy') {
      steps {
        echo 'deploy Competed'
      }
    }

  }
}