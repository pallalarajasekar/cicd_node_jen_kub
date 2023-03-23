pipeline{  
  environment {
    registry = "harinathsta1/nodejshelloworld"
    registryCredential = '660e2ab9-c41f-4473-a200-8aac9ff23ce0'
    dockerImage = ''
  }
  agent any
    stages {
        stage('Build'){
           steps{
              script{
                echo "build process"
              } 
           }   
        }
    }
}
