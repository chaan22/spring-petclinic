pipeline {
  agent any
  // JAVA와 Maven Tool 등록
  tools {
    jdk 'jdk17'
    maven 'M3'
  }

  stages {
    // GitHub에서 Jenkins로 소스코드 복사
    stage('Git Clone') {
      steps {
        git url: 'https://github.com/chaan22/spring-petclinic.git', branch: 'main'
      }
      
      
    }
    stage('Maven Build') {
      
    }
    stage('Docker Image') {

    }
    stage('Docker Image push') {

    }
    stage('SSH Publish') {
      
    }
  }
}