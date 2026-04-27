pipeline{

    agent any;
stages{
    stage('Clone Repo'){
        steps{
            echo(message: 'Cloning the repo')
           git(url: 'https://github.com/krishna-cyber/two-tier-flask-app.git',branch: 'master')
        }
    }

    stage('Build'){
        steps{
            echo(message: 'Building the docker application')
        }
    }
     stage('Test'){
         steps{
             echo(message: 'Testing the docker application')
         }
     }
     stage('Deploy'){
         steps{
             echo(message: 'Deploying the docker application')
         }
     }
        
    }
}
