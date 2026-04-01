
stage('Install Dependencies') {
            steps {
                sh '''
                pip3 install ruff pytest coverage --break-system-packages
                if [ -f requirements.txt ]; then pip3 install -r requirements.txt --break-system-packages; fi
                '''
            }
        }
