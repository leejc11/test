pipeline {
  agent any
  stages {
    stage('test111') {
      parallel {
        stage('test111') {
          steps {
            sleep 1000
          }
        }

        stage('test11') {
          steps {
            timestamps()
          }
        }

      }
    }

    stage('1111') {
      steps {
        timestamps()
      }
    }

  }
}