pipeline{
    agent any
    
        tools{
            terraform 'terraform'
        }
        stages{
            stage('cloning'){
                steps{
                    git 'https://github.com/Himabindu1785059/terraformdemo.git'
                    
                }
             }
            stage('terraform init'){
                steps{
                    sh 'terraform init'
                }
                
             }
             stage('terraform plan'){
                steps{
                    sh 'terraform plan'
                }
                
             }
             stage('terraform apply'){
                steps{
                    sh 'terraform apply --auto-approve'
                }
                
             }
             
         }
    }

    //jenik file
