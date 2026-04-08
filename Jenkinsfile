pipeline {
    agent any

    stages {
<<<<<<< HEAD
        stage('Clone Repo') {
            steps {
                git 'https://github.com/your-username/your-repo.git'
            }
        }

        stage('Build') {
            steps {
                echo 'No build needed for HTML/CSS project'
            }
        }

        stage('Test') {
            steps {
                echo 'No tests configured'
=======
        stage('Build') {
            steps {
                echo 'No build required for HTML/CSS project'
>>>>>>> attractive/design
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying project...'
<<<<<<< HEAD

                // Example: copy files to a folder
                sh 'mkdir -p /var/www/html/myproject'
                sh 'cp -r * /var/www/html/myproject/'
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