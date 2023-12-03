pipeline {
  agent any
    {   
  stages {
    stage('GitHub Jenkins') {
      steps {
        git 'https://github.com/Revs-devops-2023/Revs-devops-2023.git'
        sh cat README.md
      }
    }
  }
}
}
