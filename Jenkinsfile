pipeline{
  agent any
  stages{
    stage('Version'){
      steps{
        sh 'python -version'
      }
    }
    stage('hello'){
      steps{
        sh 'python hello.py'
      }
    }
  }
}
