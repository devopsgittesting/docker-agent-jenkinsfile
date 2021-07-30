pipeline {
  agent 
         {
         
         docker {
          image 'centos:7'
        }
      }
        
        option {
        newContainerPerStage()
        }
 
        stages
        {
          stage('build') 
          {
      steps {
        sh 'cat /etc/*-release'
      }
    }

    stage('deploy') {
      steps {
        echo 'This is Deploy Stage'
      }
    }

  }
}
