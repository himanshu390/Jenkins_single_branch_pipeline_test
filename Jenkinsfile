pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                //sh "python3 test_jenkins.py"
                sh "pwd"
                sh "sudo chmod +x test.sh"
                //input('Do you want to proceed for testing?')
                
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
                sh "./test.sh"
                
                //echo "name"
                //sh "echo \"from shell name=${name}\""
                sh '''
                "echo \"from shell name=${name}\"
                '''
                
                
                 input('Do you want to proceed for Deployment?')
               
            }
        }
        stage('Deploy') {
            steps {
                
                echo 'Deploying..'
               
                
               
            }
        }
        
        
    }
}
