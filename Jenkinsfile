pipeline {
    agent any
    options {
        skipStagesAfterUnstable()
    }
    stages {
        stage('Build') {
            steps {
                echo 'Building'
                      git 'https://github.com/newuser31/test-git-repo.git/'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing'
               
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying'
            }
        }
    }
}
