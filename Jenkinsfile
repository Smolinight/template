pipeline 
{
    agent { 
	label 'master'
	}
    stages 
    {
        stage('Firts stage') 
        {
            steps 
            {
                echo 'This is the first stage'
                sh '''
                    pwd
                    whoami
                    ls -la
                '''
            }
        }
        stage('Second stage')
        {
            steps
            {
                echo 'This is the second stage'
                echo 'Start stage....'
                sh "cat index.html"
                echo 'End stage...'
            }
        }
    }
}
