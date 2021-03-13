def pruebajenkins
pipeline{

    withCredentials([usernamePassword(
                                  credentialsId: 'variableprueba',
                                  usernameVariable: 'USERNAME',
                                  passwordVariable: 'PASSWORD'
                                )]) 
    
    agent any
    stages{

        stage('Prueba1'){
            steps{
                echo 'hola mundo'
                echo "$USERNAME"
            }
        }

    }

}
