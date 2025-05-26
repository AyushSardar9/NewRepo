pipeline{
    agent any

    stages{
        stage('Build'){
            steps{
                echo 'Build Sucessfully'
            }
        }
        stage('Run'){
            steps{
                echo 'Run Sucessfully'
                bat 'node demo.js'
            }
        }
    }
}
