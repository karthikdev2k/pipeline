node
{
  git([url: 'git://github.com/karthikdev2k/CustMgmtTest.git', branch: 'master'])
  stage('Build')
  {
    echo 'Build stage'
    echo "Path Env variable is set to: '$env.PATH'"
    echo "Build id for this Jenkins job is '$env.BUILD_ID'"
    echo "And running on Jenkins machine: '$env.JENKINS_URL'"
    echo "### GOING TO CHECKOUT SCM TO DO BUILD ###"
    checkout scm
  }
  stage('Test')
  {
    echo 'Test stage'
  }
  stage('Deploy')
  {
    echo 'Publish stage'
  }
}
