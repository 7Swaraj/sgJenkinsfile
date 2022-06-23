node {
    stage('git clone') {
     git credentialsId: 'git', url: 'https://github.com/7Swaraj/sp7777.git'
	 }
	  stage('maven version') {
		sh 'mvn --version'   
    }
    stage('maven clean') {
		sh 'mvn clean'   
    }
	stage ('maven validate') {
		sh 'mvn validate'
	}
	stage ('maven compile') {
		sh 'mvn compile'
	}
	stage ('maven test') {
		sh 'mvn test'
	}
	stage ('maven package') {
		sh 'mvn package'
	}
	stage ('maven deploy') {
		sh 'mvn deploy'
	}
	
	
}
