pipeline {
  agent any
  stages {
    stage('Build') {
      agent any
      steps {
        dir(path: 'C:\\Temp\\TP_SCM\\RepoGit\\spring-boot-jpetstore')
        sh 'git pull origin master'
        sh 'gradle build'
        sh 'gradle jar'
      }
    }

  }
}