pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        git(url: 'https://github.com/devopsdeepdive/blueocean-test-repo.git', branch: 'master', credentialsId: 'github-user')
      }
    }
    stage('Package') {
      steps {
        sh 'mvn package'
      }
    }
 stage('Deploy') {
      steps {
        echo 'Deployeing'
}
      }
    }
  }
}
