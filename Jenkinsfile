pipeline
{
    agent any
    stages
    {
        stage("GIT CHECKOUT")
        steps{git 'https://github.com/pradyumn12j/HEYtest.git'}
    }
    {
        
    stage("validattion step")
    {
    steps{withMaven(globalMavenSettingsConfig: '', jdk: 'HOME_JDK', maven: 'HOME_MAVEN', mavenSettingsConfig: '', traceability: true) {
    sh('mvn test')
}
  }}
}
    
}