pipeline{
  agent any
  stages{
    stage("code"){
      steps{
        git branch: 'main', url: 'https://github.com/bhavanaparamesh/docrepo.git'
      }
    }
      stage("build"){
        steps{
         sh "docker build -t image3 ."
        }
      }
        stage("container"){
          steps{
          sh "docker run -itd --name flm -p 2233:80 image3"
         }
     }  
  }
}

  
    
        
      
   
