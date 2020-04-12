@Library('shared') _

build = org.foo.utils.mvn.new(this)

node {
  build.mvn(this, 'clean package')
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
