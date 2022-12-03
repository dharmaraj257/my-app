pipeline {
    agent any 
    stages {
        stage('Install') { 
            steps {
                echo "install npm" 
            }
        }
        stage('Build') { 
            steps {
                echo "ng build --prod"
            }
        }
        stage('Deploy') { 
            steps {
                echo "ng serve"
            }
        }
    }
}
