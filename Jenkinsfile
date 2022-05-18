pipeline {
       agent any
       tools {
       maven '3.8.2'
       }
       stages 
       {
       stage('Build')
       {
       steps{
       echo "Building the project..."
       sh "mvn clean"
       }
       } 
    
       stage('Test')
       {
        steps{
       echo "Testing the project..."
       sh "mvn test"
       }
       }

       stage('Compile')
       {
        steps{
       echo "Compiling the project..."
       sh "mvn compile"
       }
       }

       stage('Deploy')
       {
        steps{
       echo "Deploying the project..."
       }
       }   
       }
}
