pipeline {
	agent any
	stages{
	stage('Build'){
		steps{
		echo 'Compiling the source code...'
}
}
	stage('Test'){
		steps{
		echo 'Running unit tests...'
}
}
	stage('Deploy'){
		steps{
		echo 'Deploying application to server...'
}
}
}


}