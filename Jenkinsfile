pipeline {
	agent any 
	stages {
	stage('git fetch repository') {
	steps {
		git 'https://github.com/Rajeshg1709/webs1'
		}}
	stage('run installer') {
	steps {
	sh 'sudo chmod 777 install.sh'
	sh './install.sh'
	sh 'sudo cp index.html /var/www/http/index.html'
	}}}}

