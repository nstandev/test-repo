pipeline {
    agent any
    
    stages {
        stage('Clone Repository') {
            steps {
                git branch: 'main', url: 'https://github.com/nstandev/test-repo.git'
            }
        }
        stage('Build') {
            steps {
                echo "Building the application..."
            }
        }
        stage('Test') {
            steps {
                echo "Running tests..."
            }
        }

         stage('Integrate') {
            steps {
                echo "Integrating application..."
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying application..."
            }
        }
    }
}
