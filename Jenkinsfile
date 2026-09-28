pipeline {
  agent any // This runs directly on your Built-In node, skipping Docker
  stages {
    stage('Test') {
      steps {
        echo 'Bypassed Docker! The pipeline is finally executing.'
      }
    }
  }
}
