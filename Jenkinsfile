pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        build(job: 'job1', quietPeriod: 5)
      }
    }

  }
}