pipeline {
    agent any

    stages {
        stage('Copiar repositorio Github') {
            steps {
                git branch: 'main', url: 'https://github.com/JuPalmas/pruebasPortafolio.git'
            }
        }
        stage('Ejecutando archivo python') {
            steps {
                sh 'python --version'
                sh 'python start.py'
            }
        }
    }
}
