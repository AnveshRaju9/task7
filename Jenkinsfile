node
git credentialsId: 'fa32cd45-f67b-4197-817e-4d6af4f9a7de', url: 'https://github.com/AnveshRaju9/task7.git'
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
