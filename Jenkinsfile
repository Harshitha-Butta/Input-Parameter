pipeline{
  agent any
  parameters {
  string description: 'Enter the new version : ', name: 'version', trim: true
  }
  stages{
    stage('hello'){
      steps{
      sh 'py --version'
      }
    }
    stage('printing new version'){
      steps{
      sh 'py get_version.py'
      }
    }
  }
}
