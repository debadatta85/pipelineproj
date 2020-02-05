pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            echo 'build scripts are exceuted'
          }
        }

        stage('build1') {
          steps {
            echo 'build second part of the code'
          }
        }

      }
    }

    stage('deploy') {
      steps {
        echo 'deploy the code '
      }
    }

  }
}