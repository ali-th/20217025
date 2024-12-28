pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                git 'https://github.com/ali-th/20217025.git'
            }
        }
        stage('Execute Bash Script') {
            steps {
                sh './list_files.sh'
            }
        }
    }
}

