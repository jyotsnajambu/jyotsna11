def workspace;
node
{
    stage('checkout')
    {
    checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[url: 'https://github.com/wkhanvisualpathit/VProfile.git']]])
    workspace =pwd;
    }
    stage('Stactic Code Analysis')
    {
        echo "Static Code Anaysis"
    }
    stage ('Build Review')
    {
        echo "Build Review"
    }
    stage('Code Analysis')
    {
        echo "code Analysis"
    }
    stage ('Code Review')
    {
        echo "Code Review"
    }
}
