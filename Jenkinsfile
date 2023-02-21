pipeline{
  agent { label "${agent_label}" }
  parameters {
  string description: 'Enter the new version : ', name: 'version', trim: true
  }
  stages{
    stage('hello'){
      steps{
      bat 'py --version'
      }
    }
    stage('printing new version'){
      steps{
      bat 'py get_version.py'
      }
    }
  }
}
