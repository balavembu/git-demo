pipeline {
  agent {label 'gitcheck'}
  
  stages {
    stage('Testing Git Check') {
      steps {
          sh './getlog.sh'
      }
    }
  }
}
