pipeline{
    agent any
    tools{
        nodejs 'NodeJs14'
    }
    stages{
        stage ('Build'){
            steps{
                sh 'npm install'
            }
        }
        stage ('Test'){
            steps{
                sh './jenkins/scripts/test.sh'
            }
        }
    }
}