pipeline {
    agent  any
    stages {
        stage('Parent') {
  options {
    lock('something')
  }
  stages {
    stage('one') {
        steps{
      echo 'hi'
        }
    }
    stage('two') {
                steps{
      echo 'hi again'
        }
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