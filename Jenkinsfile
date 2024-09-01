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

    environment {
        MY_VAR = 'une variable'
        MY_NUMBER = 123
    }

    stages {
        stage('build') {
            steps {
                echo ("Branch_name: ${env.BRANCH_NAME}")
                echo ("Branch_is_primary: ${env.BRANCH_IS_PRIMARY}")
                echo ("ci: ${env.CI}")
                echo ("Build_number: ${env.BUILD_NUMBER}")
                echo ("Jenkins_url: ${env.JENKINS_URL}")
                echo ("MY_VAR: ${env.MY_VAR}")
                echo ("MY_NUMBER: ${env.MY_NUMBER}")
                sh 'printenv'
            }
        }
    }
}
