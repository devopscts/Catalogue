pipeline {
    agent any 

    stages {
        stage ("Install Dependencies") {
            steps {
                sh 'npm install'
            }
        }

        stage ("Sonar Scan") {
            steps {
                sh 'sonar-scannar'
            }
        }
    }
}

