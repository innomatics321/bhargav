pipeline {
  agent any
  stages {
    stage('clone') {
      steps {
        git 'https://github.com/vignanit/Bhargav.git'
        git(url: 'https://github.com/vignanit/Bhargav.git', branch: 'master')
      }
    }

    stage('compile') {
      steps {
        bat 'mvn compile'
      }
    }

  }
}