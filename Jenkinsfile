pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        git(url: 'https://github.com/nareshkalakanti/pipeline-python-project.git', branch: 'master')
      }
    }

    stage('build') {
      steps {
        sh 'python *test.py'
      }
    }

  }
}