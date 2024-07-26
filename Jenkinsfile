pipeline {
    agent any

    stages {
        stage('pora') {
            steps {
                git branch: 'main', url: 'https://github.com/CloudTechDevOps/Terraform_CICD.git'
            }
        }
        stage('init') {
            steps {
                sh 'terraform init'
            }
        }
    }
}
