pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                git branch: 'main', url: 'https://github.com/ali-th/20217025.git'
            }
        }
        stage('Execute Bash Script') {
            steps {
                sh './ls.sh'
            }
        }
    }
}
