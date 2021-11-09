pipeline{
  agent {docker {image 'python3' }}
    stages{
        stage("Test"){
            steps{
                python3 '_2048.py'
            }
        }
    }
}
