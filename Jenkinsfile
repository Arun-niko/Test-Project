pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "Checking Environment..."
                // 'sh' runs a shell command. 'ls -la' lists all files in the workspace.
                sh 'ls -la' 
            }
        }
        stage('Test') {
            steps {
                echo "Testing stage..."
            }
        }
        stage('Deploy') {
            steps {
                echo "Deploying..."
            }
        }
    }
}
