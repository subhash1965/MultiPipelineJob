node('built-in') 
{
	stage('ContinuesDownload_loans') 
	{
    	git branch: 'main', url: 'https://github.com/subhash1965/java-demo'
  	}

    stage('ContinuesBuild_loans') 
    {
        sh 'mvn package'
    }
}
