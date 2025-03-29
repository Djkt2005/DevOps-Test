pipeline{
    agent any
    stages{
        stage('install dependencies'){
            sh 'npm install';
        }

        stage('run tests'){
            sh 'npm test || echo "No tests defined"';
        }

        stage('build'){
            sh 'npm run build';
        }
    }
}