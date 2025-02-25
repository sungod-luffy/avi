pipeline
{
agent any

stages
{
stage('clone')
{
steps{
git 'https://github.com/sungod-luffy/avi.git'
}
}
stage('build')
{
steps
{
sh 'java Hello.java'
}
}
stage('run')
{
steps
{
sh 'javac Hello.java'
}
}
}
}
