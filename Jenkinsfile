pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        git(url: 'git@github.com:giladifrah/NodeJS-EmptySiteTemplate.git', branch: 'master', credentialsId: 'giladgit-ssh')
      }
    }

  }
}