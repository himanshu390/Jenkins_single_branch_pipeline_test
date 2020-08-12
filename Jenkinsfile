pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh "python3 test_jenkins.py"
                sh "pwd"
                sh "./tesh.sh"
                sh "ls"
            }
        }
        
        
    }
}
