pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'echo "Building...."'
      }
    }

    stage('Testing') {
      steps {
        sh 'echo "Testing..."'
      }
    }

    stage('Deploye') {
      parallel {
        stage('Deploye') {
          steps {
            echo 'Deploying code'
          }
        }

        stage('Deploye2') {
          steps {
            echo 'deploye code2'
          }
        }

      }
    }

  }
}