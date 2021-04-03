pipeline{
    agent any
    stages{
        stage("Deploy do container Phyton"){
            steps{
                sh "ansible-playbook playbook.yml"
            }
        }

        stage("Verificando Imagem Container "){
            steps{
                sh "docker images"
            }
        }
    }
}