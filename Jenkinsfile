pipeline {
    agent any
    environment{
        MY_VAR = "Good evening mum I love you"
        MY_BIRTH = "15/09/1999"
    }
    stages {
        stage('build'){
            steps{
                echo "BRANCH_NAME: ${env.BRANCH_NAME}"
                echo "BRANCH_IS_PRIMARY: ${env.BRANCH_IS_PRIMARY}"
                echo "CI: ${env.CI}"
                echo "BUILD_NUMBER: ${env.BUILD_NUMBER}"
                echo "JENKINS_URL: ${env.JENKINS_URL}"
                echo "MY_VAR : ${env.MY_VAR}"
                echo "MY_BIRTH : ${env.MY_BIRTH}"
            }
        }
        
    }
}