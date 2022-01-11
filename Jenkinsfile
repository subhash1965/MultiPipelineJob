node('built-in') 
{
	stage('Continues Download') 
	{
    	git branch: 'main', url: 'https://github.com/subhash1965/java-demo'
  	}

    stage('Continues Build') 
    {
        sh 'mvn package'
    }
}
