pipeline {
    agent any
    stages{
        stage('first-stage'){
            steps{
                echo "the now"
            }
        }
        stage('2nd-stage'){
            steps{
                sh 'df -h'
            }
        }
        stage('3rd-stage'){
            steps{
                sh 'lscpu'
            }
        }
    }
}