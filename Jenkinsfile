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
        sh 'chmod +x script.sh'
        sh './script.sh'
      }
    }
  }
}
