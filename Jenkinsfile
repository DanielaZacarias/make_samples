#!groovy
pipeline {
    agent any
    stages {
        stage ("Test") {
            steps {
        sh '''
            #!/bin/bash
           make -f mkfile.r
           bash ./app
        '''
    }
}
}
}
