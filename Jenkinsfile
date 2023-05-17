pipeline{
    agent any
    tools{
        maven 'maven'
    }
    stages{
        stage('Build'){
            steps{
                git 'https://github.com/mercyfulmama/htech-finance-app'
                sh 'mvn clean install'
            }
        }
    }
}
