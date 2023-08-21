pipeline {
    agent any 
    tools {
        maven 'Maven'
    }
    stages {
        stage("build") {
            steps {
                script {
                    echo "building the application..."
                }
            }
        }
        stage("test") {
            steps {
                script {
                    echo "building the docker image..."
                    
                }
            }
        }
        stage("deploy") {
            steps {
                script {
                    echo "deploying the application..."
                }
            }
        }
    }
}

