pipeline {
  agent any
  stages{
    stage('test'){
      steps{
        sh "echo hello1 > hello.txt"
        sh "chmod 700 test.sh"
        sh "${env.WORKSPACE}/test.sh"
      }
    }
  }
}
