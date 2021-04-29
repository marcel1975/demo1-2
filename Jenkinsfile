pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        echo 'This is a $BUILD_NUMBER of the $DEMO'
      }
    }

  }
  environment {
    DEMO = '1'
  }
}