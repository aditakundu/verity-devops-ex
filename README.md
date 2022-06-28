//Code starts for stage Clean
        stage('Clean') {
            steps {
                sh 'mvn clean'
            }
        }
		//Code ends for stage Clean
		
		//Code ends for stage Clean
		
		
		//Code starts for stage PMD
		stage('PMD') {
            steps {
                sh 'mvn site'
