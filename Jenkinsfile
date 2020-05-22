node('master')
{
   stage('ContinuousDownload_branch1')
   {
      git 'https://github.com/intelliqittrainings/maven.git'
   }
   stage('ContinuousBuild_branch1')
   {
       sh label: '', script: 'mvn package'
   }
}
