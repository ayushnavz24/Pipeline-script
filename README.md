# Pipeline-script

Pipeline {
    agent any 
    stages {
        stage('Build') {
            steps {
                echo "this is build stage"
            }
        }
        stage('Test') {
            steps {
                echo "this is build stage"
            }
        }
        stage('Deploy') {
             steps {
                echo "this is build stage"
            }    
        } 
    }
}
