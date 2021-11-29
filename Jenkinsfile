pipeline {
   agent any
  
  stages{
     
     stage('Install'){
        steps{
           git 'https://github.com/shambhu1977/Terraform.git'
        }
     }
     
     stage('Terraform validate'){
        steps{
           bat '''terraform validate'''
        }
     }
    }
  }
