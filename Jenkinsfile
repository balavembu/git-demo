pipeline {
  agent any
  
  stages {
    stage('Build') {
      steps {
          echo 'Hello World'
          // git log --oneline --graph --decorate --color  
        // sh './getlog.sh'
      }
    }
    
    stage('Test') {
      steps {
          sh 'git log --oneline --graph --decorate --color'
      }
    }
  }
}
