pipeline {
    agent any
stages
{
     stage ('maven version') 
   {
            Steps
        {
          Bat label: “, script: ‘mvn -v’
        }
   }
     
         Stages ('Running Test')
 {
        steps('Test') 
         {
                Bat label: “, script: ‘mvn clean test’
            }
   }
            
  }
}
