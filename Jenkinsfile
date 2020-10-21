pipeline
{
  agent any
  stages
  {
    stage('Build Master')
	{
	  when
	  {
	    branch 'master'
	  }
	  
	  steps
	  {
	    echo "Building master branch"
	  }
	}
	    stage('Build Develop')
	{
	  when
	  {
	    branch 'develop'
	  }
	  
	  steps
	  {
	    echo "Building develop branch"
	  }
	}
  }
}