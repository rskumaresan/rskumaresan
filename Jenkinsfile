pipeline

{
    agent any
    stages
    {
        stage('Build')
        {
            steps
            {
                echo 'Build Application'
            }
        }
        
        stage('Test')
        {
            steps
            {
                echo 'Test Application'
            }
        }
        
          stage('Deploy')
        {
            steps
            {
                echo 'Deploy Application'
            }
        }
        
    }
    post
    {
        failure
        {
           mail bcc: '', body: 'Hai', cc: '', from: '', replyTo: '', subject: 'Hai', to: 'rskumaresan2013@gmail.com'
        }
    }
}
