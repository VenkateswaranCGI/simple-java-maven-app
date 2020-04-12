@Library('shared') import org.foo.*

pipeline {
  agent any
  stages {
    stage('Init') {
      steps {
        script {
          echo GlobalVars.foo
          mvn()
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
