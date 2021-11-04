pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '''echo "hello world"
'''
      }
    }

    stage('test') {
      steps {
        sh 'sudo yum install -y httpd'
        sh 'sudo systemctl start httpd'
      }
    }

  }
}