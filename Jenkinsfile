pipeline {
    agent {label 'debian'}

    stages {
        stage('cloning') {
            steps {
                git branch: 'main', url: 'https://github.com/RobertoMen2a/proyecto-final-vue.git'
            }
        }
        stage('build') {
            steps {
                sh "docker-compose up -d "
            }
        }
    }
}
