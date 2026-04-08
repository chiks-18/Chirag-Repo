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
                
<<<<<<< HEAD
                bat 'mkdir C:\\deploy\\myproject'
                bat 'xcopy /E /I /Y * C:\\deploy\\myproject'
=======
                // Create deployment folder if it doesn't exist
                bat 'if not exist C:\\deploy\\myproject mkdir C:\\deploy\\myproject'
                
                // Copy all files from Jenkins workspace to deployment folder
                bat 'xcopy /E /I /Y * C:\\deploy\\myproject'
                
                echo 'Deployment complete! Open C:\\deploy\\myproject\\index.html to see your site.'
>>>>>>> attractive/design
            }
        }
    }
}