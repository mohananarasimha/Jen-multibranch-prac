node('master') 
{
    stage('Continuous Download_loans1') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build_loans1') 
	{
    sh label: '', script: 'mvn package'
	}
}
