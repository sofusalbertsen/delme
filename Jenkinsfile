pipeline {
    agent  any
    stages {
        stage('Parent') {
  options {
    lock('something')
  }
  stages {
    stage('one') {
      echo 'hi'
    }
    stage('two') {
      echo 'hi again'
    }
  }
}

        stage('say hello') {
            steps {
                sh '''echo "hello world"'''
            }
        }
    }
}