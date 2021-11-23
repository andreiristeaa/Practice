pipeline{

    agent any
    
    environment {
        dockerImage = ''
        registry = 'andreiristeaa/repository44'
    }
    
    stages {
    
        stage('Build Docker Image') {
            steps {
                script {
                     dockerImage = docker.build registry
                        }
                   }
                }
             }
}
