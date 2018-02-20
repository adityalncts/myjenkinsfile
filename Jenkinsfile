pipeline {
  agent any
  stages {
    stage('SCM') {
      steps {
        git(url: 'https://github.com/adityalncts/javamvn.git', credentialsId: 'javamvn')
      }
    }
  }
}