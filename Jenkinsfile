pipeline {
    agent any 
    parameters {
        choice(name: 'VERSION' , choices: ['1.1.0', '1.2.0', '1.3.0'], description: '')
        booleanParam(name: 'executeTests', defaultValue: true, description: '')
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

