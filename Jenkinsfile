pipeline {
  agent any
  
  stages {
    stage('Build') {
      steps {
          git log --oneline --graph --decorate --color  
        // sh './getlog.sh'
      }
    }
  }
}
