node('master') 
{
    stage('Continuous Download_loans') 
	{
    		git branch: 'master', url: 'https://github.com/devopswithwahab/maven.git'
	}
    stage('Continuous Build_loans') 
	{
    		sh 'mvn package'
	}
}
