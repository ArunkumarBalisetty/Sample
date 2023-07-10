node('built-in') 
{
    stage('Continuous Download') 
	{
    git 'https://github.com/ArunkumarBalisetty/Sample.git'
	}
    stage('Continuous Build') 
	{
    sh 'mvn package'
	}
}
