node('built-in') 
{
    stage('Continuous Download_Loans') 
	{
    git 'https://github.com/shweta2898/MyRepo2.git'
	}
    stage('Continuous Build_Loans') 
	{
    sh label: '', script: 'mvn package'
	}

}
