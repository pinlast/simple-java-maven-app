pipeline {
	agent {
	  docker {
	    image 'maven:3-alphine'
	  }
	}
	stages{
	  stage('Build'){
	    steps{
	      sh 'mvn -B -DskipTests clean package'
	    }
	  }
	}
}
