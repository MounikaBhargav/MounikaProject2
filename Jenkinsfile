pipeline
{
    agent Jslave1
    stages
    {
        stage("Contdownload")
        {
	steps
	{
            git changelog: false, poll: false, url: 'https://github.com/MounikaBhargav/Project1.git'
        }
	}
    }
}
