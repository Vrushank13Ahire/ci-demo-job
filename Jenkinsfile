pipeline {
  agent any {
    stages {
      stage ('Checkout') {
        steps {
          checkoutscm
        }

      stage ('Build') {
        steps {
          echo "Installing Dependencies"
        }

      stage ('Test') {
        steps {
          echo "Installing Dependencies"
        }

      stage ('Deploy') {
        when {
          branch 'main'
        }
        steps {
          sh 'echo Deploying'
        }

    post {
        success {
            echo 'All stages passed'
        }
        failure {
            echo 'Something failed'
        }
    }

      }
            
