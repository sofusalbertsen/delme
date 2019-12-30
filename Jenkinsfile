pipeline {
    agent  any
    stages {
        stage('say hello') {
            steps {
                sh '''echo "hello world"'''
                sh "exit 1"
            }
        }
    }
}