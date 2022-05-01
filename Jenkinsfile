node
{
 stage('git clone')
{
 git url: 'https://github.com/shaik7866/maven-web-application.git'
}
stage('maven build')
{
    sh "mvn clean package"
}
