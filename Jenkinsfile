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
        echo 'Building...'
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
      echo 'Building...'
          }
  }
}
}
