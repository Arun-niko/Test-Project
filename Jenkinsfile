groovy id="9ikutx"

pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git url: 'https://github.com/Arun-niko/Test-Project', branch: 'main'
            }
        }
        stage('Build') {
            steps {
                echo "Pipeline Build Running..."
            }
        }
        stage('Test') {
            steps {
                echo "Testing stage..."
            }
        }
        stage('Deploy') {
            steps {
                echo "Deploy Stage"
            }
        }
    }
}
