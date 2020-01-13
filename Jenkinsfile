pipeline {
  agent any
  environment { 
        docker_username = 'praqmasofus'
  }
  stages {
    stage('clone down') {
        agent {
        label 'host'
    }
      steps {
        stash(excludes: '.git', name: 'code')
        deleteDir()
      }
    }

  }
  
}