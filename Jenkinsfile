pipeline 
{
    agent any

    stages 
    {
        stage('Build') 
        {
            steps 
            {
                echo 'Build App'
            }
        }

        stage('Test') 
        {
            steps 
            {
                echo 'Test App'
            }
        }

        stage('Deploy') 
        {
            steps 
            {
                echo 'Deploy App'
            }
        }
    }

    post
    {

    	always
    	{
            mail bcc: '', body: 'Summary of Project', cc: '', from: '', replyTo: '', subject: 'PipeLine Status', to: 'selenium3bymukesh@gmail.com'
    
    	}

    }
}
