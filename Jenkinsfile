pipeline{
  agent any
  parameters {
  string description: 'Enter the new version : ', name: 'version', trim: true
  }
  stages{
    stage('printing new version'){
      steps{
      sh 'python3 .py'
      }
    }
  }
}
