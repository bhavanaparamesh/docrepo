pipeline{
  agent any
  stages{
    stage{
      steps{
        git branch: 'main', url: 'https://github.com/bhavanaparamesh/docrepo.git'
      }
      stage{
      steps{
        sh "docker build -t image1 . "
      }
        stage{
      steps{
        sh "docker run -d --name con1 image1"
      }
    }  
   } 
  }
        
      
   
