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

    // The Post section runs after all stages are finished
    post {
        always {
            echo "I will always run, no matter what!"
        }
        success {
            echo "The build was a success! Time to celebrate."
        }
        failure {
            echo "The build failed. Check the logs above to see why."
        }
    }
}
