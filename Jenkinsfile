pipeline {
    agent any
    stages {
        stage('Upload to AWS s3') {
            steps {
                withAWS(region: 'us-east-1') {
                    s3Upload(file: 'index.html', bucket: 's3bucketforjenkinsaravind', path: 'static/index.html')
                }
            }
        }
    }
}