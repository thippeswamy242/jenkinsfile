pipeline {
    agent any

    stages {
        stage('First-Stage') {
            steps {
                echo 'Hello World'
                echo "The build number is  ${BUILD_NUMBER}"
                
            }
        }
       stage('Second-stage') {
            steps {
                echo "The build number is  ${BUILD_NUMBER}"
                echo "The build number is  ${BRANCH_NAME}"
                
            }
        } 
    }
}
