pipeline {
    agent any
    options {
        skipDefaultCheckout(true)
    }
    stages {
       stage('Checkout SCM') {
            steps {
                echo '> Checking out the source control ...'
                checkout scm
            }
        }
        stage('Test') {
            steps {
                sh '''
                echo "test-again"
                '''
            }
        }

    }
}
