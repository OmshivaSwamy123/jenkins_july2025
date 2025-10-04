pipeline
{
    agent any
    stages
    {
        stage('test')
        {
            steps
            {
                echo 'Testing Apllication'
            }
        }
        stage('Develop')
        {
            steps
            {
                echo 'Developing application'
            }
        }
        stage('Production')
        {
            steps
            {
                echo 'Moving to Production'
            }
        }
        stage('Production 2')
        {
            steps
            {
                echo 'Moving to staging due to issue '
                sh '''
                sleep 10
                exit 1
                '''
            }
        }
    }
}
