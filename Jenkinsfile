pipeline {

    agent {
        node { label 'Workstation' }
    }


    stages {
        stage('Build') {
            steps {
                echo "not required for payment"
             }
        }

        stage('Unit tests') {
            steps {
                echo "unit tests"
                // sh "python -m unittest"
             }
        }

        stage('Code Analaysis') {
            steps {
                echo "code analasys"
             }
        }

        stage('Security Scans') {
            steps {
                echo "security scans"
             }
        }

        stage('Publish a Artifact') {
            steps {
                echo "publish artifacts"
             }
        }
    }
}