pipeline {
  ant agent 
  stages {
    stage('clone') {
      steps {
        github url : 'https://github.com/Arun-2005-git/devop.git'
        branch : 'main'
      }
    }
    stage('Run Script'){
      step {
        Sh 'chmod +x script.sh'
        Sh './script.sh'
      }
    }
  }
}
