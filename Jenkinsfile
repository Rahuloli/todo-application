pipeline {
    agent any

    environment {
        GITHUB_CREDENTIALS = 'github-credentials-id'
    }

    stages {
        stage('Checkout'){
            steps {
                git credentialsID: GITHUB_CREDENTIALS
                url: 'https://github.com/Rahuloli/todo-application.git',
                branch: 'master'
            }
        }
    }
}
