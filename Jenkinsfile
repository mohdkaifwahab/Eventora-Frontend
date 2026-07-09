node('slave1'){
    stage('Checkout ....'){
        checkout scm
    }

    stage('Build Container'){
        sh 'sudo docker compose up'
    }
    
    stage('Completed..'){
        echo 'Successfull....'
    }
}