
pipeline{
    agent{
        label "slave1"
    }
    stages{
        stage("Checkout using github"){
            steps{
                checkout scm
            }
        }

        stage('Build Docker'){
            steps{
                sh 'sudo docker compose down'
                sh 'sudo docker compose up -d'
            }
        }
        stage('Compelete deployment'){
            steps{
                echo 'Successfull Completion'
            }
        }
    }
}