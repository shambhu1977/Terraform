pipeline {
   agent any
  
  stages{
     
     stage('Install'){
        steps{
           git branch: 'main', url: 'https://github.com/shambhu1977/Terraform.git'
        }
     }
     
     stage('Terraform inti'){
        steps{
           bat '''terraform init'''
        }
     }
     
     stage('Terraform plan'){
        steps{
           bat '''terraform plan'''
        }
     }
     
     stage('Terraform apply'){
        steps{
           bat'''terraform plan'''
        }
     }
     
     stage('Terraform Check'){
        steps{
           echo "Check localhost:8000"
        }
     }
     
     stage('Terraform Destory'){
        steps{
           bat'''terraform destroy'''
        }
     }
    }
  }
