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
                //name=input("What is your name?")
                sh "read name"
                sh "./test.sh $name"
                
                //echo "name"
                //sh "echo \"from shell name=${name}\""
               //sh "name=$name"
               sh '''
                 //$name
                 pwd
                 ls
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
