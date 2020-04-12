jsl = library(
  identifier: "jenkins-pipeline-shared@master",
  retriever: modernSCM(
    [
      $class: 'GitSCMSource',
      remote: 'https://github.com/VenkateswaranCGI/jenkins-pipeline-shared.git'
    ]
  )
)

import org.foo.GlobalVars

pipeline {
  agent any
  stages {
    stage('Init') {
      steps {
        script {
          echo GlobalVars.foo
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
