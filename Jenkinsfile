pipeline {
  agent any
  stages {
    stage('fetch code') {
      steps {
        git(url: 'https://github.com/awadhutvaishu/first-html-app.git', branch: 'main')
      }
    }

    stage('install apache2') {
      steps {
        sh 'sudo apt install apache2 -y'
      }
    }

  }
}