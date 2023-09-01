node('built-in') 
{
    stage('Continuous Download') 
	{
    git 'https://github.com/devopswithwahab/maven.git'
	}
    stage('Continuous Build_loans') 
	{
    sh label: '', script: 'mvn package'
	}
}
