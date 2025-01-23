pipeline{
  agent any
  stages{
    stage{
      steps{
        git branch: 'main', url: 'https://github.com/bhavanaparamesh/docrepo.git'
      }
    }
      stage{
      steps{
        sh "docker build -t image3 . "
       }
      }
        stage{
      steps{
        sh "docker run -d --name con3 image3"
       }
    }  
  }
}

  
    
        
      
   
