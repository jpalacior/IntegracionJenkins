def pruebajenkins
pipeline{

    agent any
    stages{

        stage('Prueba1'){
            steps{
                echo 'hola mundo'
                withCredentials([usernamePassword(
                                                  credentialsId: 'variableprueba',
                                                  usernameVariable: 'USERNAME',
                                                  passwordVariable: 'PASSWORD'
                                                )]) {
                                                  echo "usuario: $USERNAME, contraseña:$PASSWORD"
                                                }
            }
        }

    }

}
