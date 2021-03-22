
pipeline {
	agent any

	stages {
        stage('stage 1') {
			
            steps {
				// Timeout - abort rest of pipeline is timeout reached.		unit: [MILLISECONDS, SECONDS, MINUTES, HOURS]
				timeout(time: 5, unit: 'SECONDS') {
    				sh 'sleep 6'
				}
            }
        }
    }

}