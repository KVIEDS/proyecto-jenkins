pipeline {
    agent any
    
    stages {
        stage('Checkout') { 
            steps {
                git url: 'https://github.com/TU_USUARIO/proyecto-jenkins.git', branch: 'main'
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
