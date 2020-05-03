pipeline {
  agent any
  stages {
    stage('initial') {
      steps {
        echo 'starting'
      }
    }

    stage('build') {
      steps {
        build 'build'
      }
    }

    stage('post_build') {
      steps {
        echo 'done'
      }
    }

  }
}