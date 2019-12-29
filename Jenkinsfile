pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        git 'https://github.com/newuser31/test-git-repo.git/'
      }
    }

    stage('Depoly') {
      steps {
        echo 'Biuld is done'
      }
    }

  }
}