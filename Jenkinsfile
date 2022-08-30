pipeline {
  agent any
  environment {
    DEMO = '1-2'
  }
  stages {
    stage('stage1') {
      steps {
        echo "This is build $BUILD_NUMBER of demo $DEMO"
      }
    }
  }
}
