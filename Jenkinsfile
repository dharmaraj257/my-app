pipeline {
    agent any 
    stages {
        stage('Install') { 
            steps {
                sh "install npm" 
            }
        }
        stage('Build') { 
            steps {
                sh "ng build --prod"
            }
        }
        stage('Deploy') { 
            steps {
                sh "ng serve --port 4200"
            }
        }
    }
}
