pipeline {
  agent any
  stages {
    stage('checkout code') {
      parallel {
        stage('checkout code') {
          steps {
            git(url: 'https://github.com/ichouBA/jenkensTP', branch: 'main')
          }
        }

        stage('error') {
          steps {
            sh 'ls -la'
          }
        }

      }
    }

    stage('') {
      steps {
        sh 'npm i && npm run test:unit'
      }
    }

  }
}