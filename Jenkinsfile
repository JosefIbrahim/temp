pipeline{
    agent any

    stages {
        stage('Packer'){
            steps {
                sh ("packer build packer.json")
            }
        }
    }
}
