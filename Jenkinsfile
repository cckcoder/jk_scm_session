pipeline {
  agent any
  environment {
    DEMO = '1-2'
    NUMBER_ONE = '1'
    NUMBER_TWO = '2'
  }
  stages {
    stage('stage1') {
      steps {
        echo "This is build $BUILD_NUMBER of demo $DEMO"

        sh '''
          echo "Using a multi-line shell step"
          chmod +x test_script.sh 
          ./test_script.sh
        '''
      }
    }
  }
}
