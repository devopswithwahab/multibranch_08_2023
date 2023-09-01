node('master') 
{
    stage('Continuous Download_loans') 
	{
    		git branch: 'loans', url: 'https://github.com/devopswithwahab/maven.git'
	}
    stage('Continuous Build_loans') 
	{
    		sh 'mvn package'
	}
}
