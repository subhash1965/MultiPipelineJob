node('built-in') 
{
	stage('ContinuesDownload_master') 
	{
    	git branch: 'main', url: 'https://github.com/subhash1965/java-demo'
  	}

    stage('ContinuesBuild_master') 
    {
        sh 'mvn package'
    }
}
