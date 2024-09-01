// pipeline {
//     agent any 
// 
//     stages {
//         stage('build') {
//             steps {
//                 echo 'Build applicaiton'
//             }
//         }
//         stage('test') {
//             steps {
//                 echo 'test application'
//             }
//         }
//         stage('deployment'){
//             steps {
//                 echo 'deployment application *'
//             }
//         }
//     }
// }
pipeline {
    agent any 

    stages {
        stage('build') {
            steps {
                echo ("Branch_name: ${env.BRANCH_NAME}")
                echo ("Branch_is_primary: ${env.BRANCH_IS_PRIMARY}")
                echo ("ci: ${env.CI}")
                echo ("Build_number: ${env.BUILD_NUMBER}")
                echo ("Jenkins_url: ${env.JENKINS_URL}")
            }
        }
    }
}
