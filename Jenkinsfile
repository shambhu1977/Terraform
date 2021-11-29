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
    }
  }
