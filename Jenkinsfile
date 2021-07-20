  
node('jenkins-slave') {
    
     stage('test pipeline') {
        sh(script: """
            echo "hello"
           git clone https://github.com/RakVanu/WPApplication.git
           cd ./docker-development-youtube-series/golang
           
           docker build . -t test
        """)
    }
}
   
          

