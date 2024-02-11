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

        stage('') {
          steps {
            sh 'ls -la'
          }
        }

      }
    }

  }
}