@Library('shared') import org.foo.GlobalVars

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
