pipeline{
    environment{
            DOCKERHUB = credentials('DockerHubCred')
            ANSIBLE_VAULT_PASSWORD = credentials('ANSIBLE_VAULT_PASSWORD')
    }
    agent any
    stages{
        stage("Git Cloning Stage"){
            steps{
                git 'https://github.com/ARJUN1220/SPE_frontend.git'
            }
        }
        stage("Docker Login"){
            steps{
               sh 'docker login -u $DOCKERHUB_USR -p $DOCKERHUB_PSW'
            }
        }
        stage("Building Docker Image"){
            steps{
                sh 'docker build -t arjun201/aj-frontend:1.0 .'
            }
        }
        stage("Pushing Docker Image on DockerHub"){
            steps{
                sh 'docker push arjun201/aj-frontend:1.0'
            }
        }
        stage("Ansible Stage"){
            steps{
                ansiblePlaybook(
                inventory: 'inventory',
                playbook: 'playbook.yaml',
                vaultCredentialsId: 'ANSIBLE_VAULT_PASSWORD')
            }
        }
    }
}

