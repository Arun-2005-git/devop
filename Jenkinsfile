Pipeline {
  Any Agent 
  Stages {
    stage('clone') {
      steps {
        github url : 'https://github.com/Arun-2005-git/devop.git'
        branch : 'main'
      }
    }
    Stage('Run Script'){
      step {
        sh 'chmod +x script.sh'
        sh './script.sh'
      }
    }
  }
}
