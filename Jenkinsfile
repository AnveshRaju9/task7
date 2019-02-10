pipeline 
{
  agent any
  triggers {
       upstream 'firstjob, First-job'
  }
  stages 
  {
    stage('FIRST-JOB')
    {
      steps { 
        echo 'https://github.com/AnveshRaju9/task7.git'
          }
    }
  }
triggers {
       downstream 'secondjob, Second-job'
}
stages {
  stage ('SECOND-JOB')
  {
    steps {
      echo 'https://github.com/AnveshRaju9/task7.git'
          }
  }
}
}
