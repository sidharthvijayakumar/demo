pipeline{
          agent any
          stages{
                  stage("One"){
                        steps{
                              git 'https://github.com/sidharthvijayakumar/demo'
                         }
                  
                  }
                  stage("Two"){
                        steps{
                              input('Do you want to proceed?')
                        }
                  
                  }
                  stage("Three"){
                    
                       when{
                              not{
                                  brach"master"
                              
                              }
                       }
                       steps{
                            echo "hello"
                       
                       }
                    
                  
                  }
          
          }




}
