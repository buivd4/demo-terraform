pipeline {
    agent {
        label 'macos'
    }

    stages {
        stage('Provision Terraform deployment') {
            steps {
                sh '/opt/homebrew/bin/terraform apply -auto-approve'
            }
        }
    }
}

