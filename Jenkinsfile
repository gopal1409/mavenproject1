pipeline {
    agent any
    tools {
        maven "localmaven"
    }
    stages {
        stage('SCM Checkout'){
            steps{
                git 'https://github.com/gopal1409/mavenproject1.git'
            }
        }
    }
}
