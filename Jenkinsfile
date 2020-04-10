@Library('shared') _
pipeline{
agent any
stages
{
    stage("Start"){
        steps{
            sendNotifications "Started"
        }
    }

        
    stage("Maven Build"){
        steps{
            mavenbuild()
        }
    }
}    
}
