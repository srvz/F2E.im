pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        sh '''echo "$ABC"
echo "$EFG"'''
      }
    }
  }
  environment {
    ABC = 'lolol'
    EFG = 'hahah'
  }
}