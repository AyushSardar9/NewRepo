pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/AyushSardar9/NewRepo.git'
            }
        }

        stage('Display HTML') {
            steps {
                publishHTML(target:[
                    reportName:'HTML page',
                    reportDir:'.',
                    reportFiles:'index.html',
                    keepAll:true,
                    alwaysLinkToLastBuild:true,
                    allowMissing:false
                ])
            }
        }
    }
}


