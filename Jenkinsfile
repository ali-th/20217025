pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                git 'https://github.com/ali-th/list-files-alihammad.git'
            }
        }
        stage('Execute Bash Script') {
            steps {
                sh './list_files.sh'
            }
        }
    }
}

