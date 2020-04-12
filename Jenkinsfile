jsl = library(
  identifier: "shared@master",
  retriever: modernSCM(
    [
      $class: 'GitSCMSource',
      remote: 'https://github.com/VenkateswaranCGI/jenkins-pipeline-shared.git'
    ]
  )
)
//@Library('shared') _

build = js1.org.foo.utils.new(this)

pipeline{
  agent any
  stages {
  stage("Maven Build"){
        steps {
        script {
          echo 'Stage 2'
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
