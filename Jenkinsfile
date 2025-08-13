pipeline {
    agent { label 'webs-agent' }
    stages {
        stage('Build Website') {
            steps {
                sh 'echo "Website build step - nothing to compile"'
            }
        }
        stage('Deploy Website') {
            steps {
                sh 'sudo cp -r website_files/* /var/www/html/'
            }
        }
    }
}

