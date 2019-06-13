node('docker') {
    checkout scm
    stage('build') {
		withMaven (maven: 'Maven 3.6.1') {
		sh label: '', script: 'mvn clean install'
}
    }
}
