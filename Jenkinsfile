pipeline {
  agent any
  stages {
    stage('Build') {
        steps ('Starting Jobs'){
          build 'JobA'
        }
          steps ('Starting Sub Jobs') {
             build 'JobB'
} 
       steps ('Starting Sub Jobs') {
   build 'JobC'
}
  }
    stage('Test') {
      steps {
        echo 'Testing..'
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deploying....'
      }
    }
  }
}
