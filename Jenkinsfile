pipeline {
agent any 
tools {
maven 'maven'
}

stages {
stage("Git Checkout"){
steps{
git 'https://github.com/JaganPothina/DevOps-ProjectMedicure.git'
 }
 }
stage('Build the application'){
steps{
echo 'cleaning..compiling..testing..packaging..'
sh 'mvn clean install package'
 }
 }
