// @Library("my-jenkins-library")_

// stage("Test post script"){
//     echo "Test post script"
// }

//      post {
//                 failure {
//                     sendEmailNotification  "FAILED"
//                 }
                 
//      }

 
    stages {
        stage('Example') {
            steps {
                echo 'Hello World'
            }
        }
    }
    post { 
        always { 
            echo 'I will always say Hello again!'
        }
    }
