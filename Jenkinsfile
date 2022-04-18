pipeline 
{
    agent any

    stages 
    {
        stage('Build') 
        {
            steps 
            {
                echo 'Build App one'
            }
        }

        stage('Test') 
        {
            steps 
            {
                echo 'Test App two'
            }
        }

        stage('Deploy') 
        {
            steps 
            {
                echo 'Deploy App three'
            }
        }
    }

    post
    {

    	always
    	{
    		emailext body: 'Summary', subject: 'Pipeline Status', to: 'selenium3bymukesh@gmail.com'
    	}

    }
}
