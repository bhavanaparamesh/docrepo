pipeline{
  agent any
  satages{
    stage{
      steps{
        git branch: 'main', url: 'https://github.com/bhavanaparamesh/docrepo.git'
      }
    }
      stage{
      steps{
        sh "docker build -t image2 . "
       }
      }
        stage{
      steps{
        sh "docker run -d --name con2 image2"
       }
    }  
  }
}

  
    
        
      
   
