pipeline {
  any agent
  Stages {
    Stage('clone') {
      Steps {
        github url : 'https://github.com/Arun-2005-git/devop.git'
        branch : 'main'
      }
    }
    Stage('Run Script'){
      Step {
        sh 'chmod +x script.sh'
        sh './script.sh'
      }
    }
  }
}
