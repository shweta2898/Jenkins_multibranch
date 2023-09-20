node('built-in') 
{
    stage('Continuous Download_master') 
	{
    git 'https://github.com/shweta2898/MyRepo2.git'
	}
    stage('Continuous Build_master') 
	{
    sh label: '', script: 'mvn package'
	}
 
}
