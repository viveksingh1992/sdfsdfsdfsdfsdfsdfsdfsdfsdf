pipeline {

	agent any
	
	stages{
		stage('Compile Stage'){
				steps{
					withMaven(maven : 'Maven Installations'){
							bat 'mvn clean compile'
						}
					}
				}
		stage('Testing Stage'){
				steps{
					withMaven(maven : 'Maven Installations'){
							bat 'mvn clean test'
						}
					}
				}
			}
		}
