node
{
stages
{
stage ('Checkout')
{
git 'https://github.com/karty333/Multibranch.git'
}
stage ('Build')
{
bat 'mvn compile'
bat 'mvn clean package'
}
}
}
