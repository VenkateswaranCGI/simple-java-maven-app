@Library('shared') import org.foo.Utilities
def utils = new Utilities(this)
node {
  utils.mvnbuild 'clean package'
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
