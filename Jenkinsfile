jsl = library(
  identifier: "jenkins-shared-library@master",
  retriever: modernSCM(
    [
      $class: 'GitSCMSource',
      remote: 'https://github.com/hoto/jenkins-shared-library.git'
    ]
  )
)

build = jsl.com.mycompany.jenkins.Build.new(this)

pipeline {
  agent any
  stages {
    stage('Init') {
      steps {
        script {
          build.setBuildDescription(
            message: "test",
            description: "test"
          )
        }
      }
    }

  }
}



//@Library('shared') _
//pipeline{
//agent any
//stages
//{
//    stage("Start"){
//        steps{
//            sendNotifications "Started"
//        }
//    }
        
//    stage("Maven Build"){
//        steps{
//            mavenbuild()
//        }
//    }
//}    
//}
