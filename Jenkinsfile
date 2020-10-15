pipeline{
          agent any
          stages{
                  stage("One"){
                        steps{
                              echo"Hello world,this is sidharth"
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
