pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/AyushSardar9/NewRepo.git'
            }
        }

        stage('Display HTML') {
            steps {
                bat 'start index.html'
            }
        }
    }
}

