pipeline{
  agent {docker {image 'ubuntu' }}
    stages{
        stage("Test"){
            steps{
                python3 '_2048.py'
            }
        }
    }
}
