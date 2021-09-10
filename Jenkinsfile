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
          script {
            env.GIT_COMMIT_MSG = sh (script: 'git log -1 --pretty=%B ${GIT_COMMIT}', returnStdout: true).trim()
        }
      }
    }
  }
}
