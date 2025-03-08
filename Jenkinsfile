pipeline 
{
    agent {
        label 'slave123'
    }
    stages
    {
        stage('build ')
        {   
            steps {

                     sh 'pwd'
                   }
        }

         stage('test_multiple')
         { 
            parallel {

             stage('test1'){
                steps {
             
                sh 'sleep 10'
                  }
                        } 

                         stage('test2'){
                steps {
             
                sh 'ls'
                  }
                        } s
                              } 
        }
    }  
    
}