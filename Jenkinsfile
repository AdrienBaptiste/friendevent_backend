pipeline {
    agent any  

    stages {
        stage('Checkout') {
            steps {
                git branch: 'dev', url: 'https://github.com/AdrienBaptiste/friendevent_backend.git'
            }
        }
        
        stage('Backend Build') {
            steps {
                echo "C'est l'étape Backend"
                echo "Le backend est prêt pour les étapes de build."
            }
        }
    }
}