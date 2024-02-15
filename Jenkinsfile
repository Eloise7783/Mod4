pipeline {
  agent any
  stages {
    stage('list all'){
      steps {
        sh "ls"
      }
    }
    stage(‘print hello’){
        steps {
            sh “echo "hello"”
        }
    }
    stage(‘create file’){
        steps {
            sh “touch "pipelinefile1"”
        }
    }
}
