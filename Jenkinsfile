pipeline {
    agent any

    stages 
    {
        stage('Build') 
        {
            steps 
            {
                echo 'Thisdfghjkbsdfdfujhj jhgjgjhkhkjwebhook'
            }
        }
        stage('Test') 
        {
            steps 
            {
                echo 'This is to test an App'
            }
        }
        stage('Deploy') 
        {
            steps 
            {
                echo 'This is to deploy an App'
            }
        }
    }
	post
	{
		always
		{
			emailext body: 'sdfghjkuytfvbnmkjbn', replyTo: 'shwetajs.lrn@gmail.com', subject: 'dfghjk', to: 'shwetajs.lrn@gmail.com'
		}
	}
}
