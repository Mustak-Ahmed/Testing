pipeline {
    agent any
    stages {
        stage('Welcome Step') {
            steps { 
                echo 'Welcome to LambdaTest'
            }
        }
        stage('Index file step') {
            steps { 
                sh 'sudo cp index.html /var/www/html/index.html'
            }
        }
    }
}
