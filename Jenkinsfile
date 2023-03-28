pipeline{
	agent any
	stages{
		stage('1-cloning'){
			steps{
				checkout scmGit(branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[credentialsId: 'team5-id', url: 'https://github.com/Team5-group6/Cronjob.review.git']])
			}
		}
		stage('2-saada1-contribution'){
			steps{
				sh 'lscpu'
				sh 'sudo systemctl status jenkins'
			}
		}
		stage('3-saada2-contribution'){
			steps{
				sh 'du -h'
				sh 'df -h'
			}
		}	
	}
}

