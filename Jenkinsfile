//@Library('shared') import org.foo.GlobalVars
@Library('shared') import org.foo.utils
def utils = new utils()

pipeline {
  agent any
  stages {
    stage('Init') {
      steps {
        script {
          //echo GlobalVars.foo
          utils.mvn(this)
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
