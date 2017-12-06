pipeline {
    agent any
    stages {
        /* "Build" and "Test" stages omitted */

        stage('Deploy - Staging') {
            steps {
                echo 'hello'
            
            }
        }

        stage(‘Deploy QA’) {
            steps {
                input "Does the staging environment look ok?"
            }
        }

        stage('Deploy - Production') {
            steps {
                echo ' production'
            }
        }
    }
}
