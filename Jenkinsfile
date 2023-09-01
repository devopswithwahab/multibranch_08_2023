node('master') 
{
    stage('Continuous Download_loans_2') 
	{
    		git branch: 'loans', url: 'https://github.com/devopswithwahab/maven.git'
	}
    stage('Continuous Build_loans_2') 
	{
    		sh 'mvn package'
	}
}
