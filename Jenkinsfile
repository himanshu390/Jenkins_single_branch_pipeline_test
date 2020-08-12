pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh "python3 test_jenkins.py"
                sh "pwd"
                sh "./test.sh"
                sh "ls"
            }
        }
        
        
    }
}
