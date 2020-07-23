pipeline {
  agent any
  stages {
    stage('stage 1') {
      parallel {
        stage('stage 1') {
          steps {
            echo 'stage 1 success'
          }
        }
        stage('Stage1 P') {
          steps {
            echo 'stage1 parallel success'
          }
        }
      }
    }
    stage('Stage 2') {
      steps {
        echo 'stage 2 successful'
      }
    }
    stage('Stage3'){
      steps {
        echo "Stage 3 Successful"
      }
    }
  }
}
