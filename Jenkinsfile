pipeline {
  agent any
	
stages {
    stage('Checkout From SCM') {
      steps {
       echo "checkout"
      }
    }
    
     stage('Build') {
      steps {
       echo "checkout"
      }
    }
    
     stage('UnitTest') {
      steps {
       echo "UnitTest"
      }
    }
    
     stage('Sonar') {
      steps {
       echo "Sonar"
      }
    }
    
    stage('Checkin to Binary Repo') {
      steps {
       echo "Checkin"
      }
    }
    
     stage('Download from Binary Repo') {
      steps {
       echo "Download"
      }
    }
    
     stage('Deploy apps to App server') {
      steps {
       echo "Deploy"
      }
    }
     
}
