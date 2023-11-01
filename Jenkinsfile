pipeline
{
   agent any

   stages
   {
    stages('Build') 
   {
   steps
   {
      echo 'Build App'
      }
     }

     stage ('Build1')
     {
      steps 
       {
       echo 'Build1 App'
       }
      }
       stage ('Test')
       {
        steps
	{
	 echo 'Test App'
	 }
	}
	 stage ('Deploy')
	 {
	  steps
	  {
	   echo 'Deploy App'
	   }
	  }
	 }
	}
