pipeline {
    agent any

    tools {
        git 'Default'
    }

    stages {
        stage("Checkout") {
            steps {
                script {
                    git "https://github.com/hetp4401/Jenkins-Test.git"
                    sh 'ls'
                }
            }
        }
    }
}
