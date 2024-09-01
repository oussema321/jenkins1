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
            print("Branch_name: ${ env.BRANCH_NAME}")
            print("Branch_is_primary: ${ env.BRANCH_IS_PRIMARY}")
            print("ci: ${ env.CI}")
            print("Build_number: ${ env.BUILD_NUMBER}")
            print("Jenkins_url: ${ env.JENKINS_URL}")
        }
    }
}