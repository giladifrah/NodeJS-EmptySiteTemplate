pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        git(url: 'git@github.com:giladifrah/NodeJS-EmptySiteTemplate.git', branch: 'master', credentialsId: 'giladgit-ssh')
      }
    }

    stage('Build') {
      steps {
        echo 'Ahlan'
      }
    }

    stage('Test') {
      steps {
        sleep 5
      }
    }

    stage('Pack') {
      steps {
        echo 'Salamat'
      }
    }

  }
}