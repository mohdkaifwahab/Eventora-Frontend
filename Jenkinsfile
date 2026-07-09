node('slave1'){
    stage('Checkout ....'){
        checkout scm
    }

    stage('Build Container'){
        sh 'docker compose up'
    }
    
    stage('Completed..'){
        echo 'Successfull....'
    }
}