pipeline {
    agent any 

    environment {
        APP_NAME = 'MyGraveyApp'
    }

    stages {
        stage('Build') {
            steps {
                echo "🔨 Building ${env.APP_NAME}..."
            }
        } // Closes Build Stage

        stage('Test') {
            steps {
                echo "🧪 Running Tests..."
            }
        } // Closes Test Stage

        stage('Deploy') {
            steps {
                echo "🚀 Deploying Application..."
            }
        } // Closes Deploy Stage
    } // Closes All Stages

    post {
        success {
            echo '✅ Pipeline finished successfully!'
        }
        failure {
            echo '❌ Pipeline failed.'
        }
    } // Closes Post
} // Closes Pipeline
