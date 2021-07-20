     stage('test pipeline') {
        sh(script: """
            echo "hello"
           git clone https://github.com/RakVanu/WPApplication.git
           cd ./dockerApp
           
           docker build . -t test
        """)
    }

