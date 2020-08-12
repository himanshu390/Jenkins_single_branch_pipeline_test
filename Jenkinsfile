pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh "python3 test_jenkins.py"
                sh "pwd"
                sh "sudo chmod +x test.sh"
                sh "./test.sh"
                sh "read -p "himanshu""
                sh "ls"
            }
        }
        
        
    }
}
