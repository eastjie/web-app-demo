@Library("my-jenkins-library")_
testMyJenkinsStages()

     post {
          changed {
                    sendEmailNotification buildChanged: true, state: "Changed"
                }
                failure {
                    sendEmailNotification buildChanged: false, state: "Failed"
                }
                unstable {
                    sendEmailNotification buildChanged: false, state: "Unstable"
                }
     }