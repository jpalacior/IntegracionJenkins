def pruebajenkins
pipeline{

    
    
    agent any
    stages{

        stage('Prueba1'){
           withCredentials([usernamePassword(
                                  credentialsId: 'variableprueba',
                                  usernameVariable: 'USERNAME',
                                  passwordVariable: 'PASSWORD'
                                )]) 
            steps{
                echo 'hola mundo'
                echo "{$USERNAME}"
            }
        }

    }

}
