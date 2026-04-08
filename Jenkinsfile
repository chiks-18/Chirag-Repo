pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'No build required for HTML/CSS project'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying project...'
                
                bat 'mkdir C:\\deploy\\myproject'
                bat 'xcopy /E /I /Y * C:\\deploy\\myproject'
            }
        }
    }
}