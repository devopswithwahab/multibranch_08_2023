node('master') 
{
    stage('Continuous Download') 
	{
    		git branch: 'master', url: 'https://github.com/devopswithwahab/maven.git'
	}
    stage('Continuous Build') 
	{
    		sh 'mvn package'
	}
}
