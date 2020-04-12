jsl = library(
  identifier: "jenkins-pipeline-shared@master",
  retriever: modernSCM(
    [
      $class: 'GitSCMSource',
      remote: 'https://github.com/VenkateswaranCGI/jenkins-pipeline-shared.git'
    ]
  )
)

build = jsl.org.foo.utils.new(this)

pipeline {
  agent any
  stages {
    stage('Init') {
      steps {
        script {
          build.mvn()
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
