pipeline {
    agent any
    
    stages {
        stage('Checkout') { 
            steps {

                git url: 'https://github.com/KVIEDS/proyecto-jenkins.git', branch: 'main'

                git url: 'file:///C:/Windows/System32/proyecto-jenkins', branch: 'main'
 f3230f0 (Agregado Jenkinsfile para pipeline)
            }
        }
        
        stage('Build') { 
            steps {
                echo 'Compilando el código...'
                sh 'echo "Simulación de build exitosa"'
            }
        }
        
        stage('Test') { 
            steps {
                echo 'Ejecutando pruebas automatizadas...'
                sh 'echo "Pruebas completadas exitosamente"'
            }
        }
        
        stage('Deploy Simulation') { 
            steps {
                echo 'Simulando despliegue...'
                sh 'echo "Despliegue exitoso"'
            }
        }
    }
}
