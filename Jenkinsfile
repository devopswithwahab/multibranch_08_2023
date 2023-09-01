node('master') 
{
    stage('Continuous Download') 
	{
    		git branch: 'master', url: 'https://github.com/devopswithwahab/multibranch_08_2023.git'
	}
    stage('Continuous Build') 
	{
    		sh 'mvn package'
	}
}
