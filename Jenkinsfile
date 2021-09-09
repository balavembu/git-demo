pipeline {
  agent {label 'gitcheck'}
  
  stages {
    stage('Testing Git Check') {
      steps {
          sh git status > current_state.csv
      }
    }
  }
}
