node('master') 
{
    stage('Continuous Download-master') 
	{
    git 'https://github.com/dhana0102/mycode.git'
	}
    stage('Continuous Build-master') 
	{
    sh label: '', script: 'mvn package'
	}
    
	}
}
