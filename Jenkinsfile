pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        echo 'This is a build $BUILD_NUMBER of demo $DEMO'
        sh 'echo "This is build $BUILD_NUMBER of demo $DEMO"'
      }
    }

  }
  environment {
    DEMO = '1'
  }
}