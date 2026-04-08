pipeline {
    agent any

    stages {
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
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying project...'

                // Example: copy files to a folder
                sh 'mkdir -p /var/www/html/myproject'
                sh 'cp -r * /var/www/html/myproject/'
            }
        }
    }
}