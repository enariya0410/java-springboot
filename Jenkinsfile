pipeline {
    agent any
    stages {
        stage('Build'){
            steps{
                echo 'Build'
                sh 'mvn clean package'
            }
        }
        stage('Test'){
            steps{
                echo 'Test'
                sh 'mvn test'
            }
        }
        stage('QA-SONAR QUBE'){
            steps{
                echo 'QA-SONAR QUBE'
            }
        }
        stage('Sonar Analysys stage'){
            steps{
                echo 'majamtytytytya'
            }
        }
        stage('Deploy to Dev'){
            steps{
                echo 'Deploy to Dev'
            }
        }
        stage('Deploy to QA'){
            steps{
                echo 'Deploy to QA'
            }
        }
        stage('Deploy to UAT'){
            steps{
                echo 'Deploy to UAT'
            }
        }
        stage('Deploy to STAGING'){
            steps{
                echo 'Deploy to STAGING'
            }
        }
        stage('Deploy to PRODUCTION'){
            steps{
                echo 'Deploy to PRODUCTION'
            }
        }

        }
        post {
            failure{
                echo 'Failure'
            }
            success{
                echo 'success but aborted too'
            }
           
        }
}
