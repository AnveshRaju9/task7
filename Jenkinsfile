pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Building..'
      }
      {
          stage ('Starting Sub Jobs') {
             build 'JobB'
} 
}
       {
       stage ('Starting Sub Jobs') {
   build 'JobC'
}
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
