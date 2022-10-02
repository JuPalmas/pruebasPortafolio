pipeline {
    agent any

    stages {
        stage('Copiar repositorio Github') {
            steps {
                git branch: 'main', url: 'https://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@github.com/DeveloperFlack/portafolio_ingenieria_2022'
            }
        }
        stage('Ejecutando archivo python') {
            steps {
                sh 'python --version'
                sh 'python start.py'
            }

    }
}
