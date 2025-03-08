pipeline 
{
    agent {
        label 'slave123'
    }
    stages
    {
        stage('build')
        {   
            steps {

                     sh 'pwd'
                   }
        }

         stage('test')
         {
             steps {
             
                sh 'sleep 10'
                    } 
        }
    }  
    
}