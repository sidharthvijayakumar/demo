pipeline{
          agent any
          stages{
                  stage("One"){
                        steps{
                              git 'git@github.com:sidharthvijayakumar/demo.git'
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
