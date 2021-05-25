pipeline {
	agent any
	stages {
		stage('Build') {
			steps {
				echo "Etape de build"
				sh 'python --version'
			}
		}
		stage('Test') {
			steps {
				echo "Etape de test"
				sh 'python3 --version'
			}
		}
		stage('Deploy') {
			steps {
				echo "Etape de déploiement"
			}
		}
	}
}
