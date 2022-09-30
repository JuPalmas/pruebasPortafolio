pipeline {
    agent any

    stages {
        stage('Build Github') {
            steps {
                echo 'Hello World'
                git branch: 'main', url: 'https://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@github.com/DeveloperFlack/portafolio_ingenieria_2022'
            }
        }
        stage('Ejecutando archivo python') {
            steps {
                bat 'python --version'
                bat 'python start.py'
            }
        
    }
}
