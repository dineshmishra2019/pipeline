pipeline {
    agent any
    stages
    {
        stage('Git clone')
        {
            steps{
                 sh 'git clone https://github.com/dineshmishra2019/test1.git'
            }
        }
        
        stage('Code stability')
        {
            steps{
                sh 'cd /var/lib/jenkins/workspace/TestPipeline'
              sh 'mvn compile'
            }
        }
    }
    
}
