pipeline{

    agent any

// uncomment the following lines by removing /* and */ to enable
    tools{
       nodejs 'nodejs' 
    }
    

    stages{
        stage('compile'){
            steps{
                echo 'npm install'
                sh 'uptime'
                sleep 4
            }
        }
        stage('test'){
            steps{
                echo 'npm test'
                sh 'uptime'
                sleep 9
            }
        }
        stage('package'){
            steps{
                echo 'npm package'
                sh 'uptime'
                sleep 7
            }
        }
    }
    
    post{
        always{
            echo 'this pipeline has completed...'
        }
        
    }
    
}
