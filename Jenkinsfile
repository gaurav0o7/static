pipeline{
        agent any
        stages {
            stage('Lint HTML'){
                steps {
                    sh 'tidy -q -e *.html"'
                    sh '''
                        echo "Multiline shell steps works too"
                        ls -lah
                        '''
                }
            }
            
        }
    }
