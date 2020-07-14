node
{
  stage ('prueba')
  {
    if (env.GIT_BRANCH == 'Footer' )
    {
      echo "vamos por buen camino"
    }
    else
    {
      echo "Falta algo"
    }
  }
  stage('checkout')
  {
    checkout scm
    echo "hola munod"
  }
  
}
