pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
				  bat "rmdir  /s /q POC-Jenkins"
                  bat "git clone https://github.com/CarolinaDoncel/POC-Jenkins.git"
                  sh '''#!/bin/bash
                  google-chrome --version
                  chmod -R 777 *
                  aimaps/Gsqa.Tools.AiMaps.Console src='Mapa/MapasPOC.aiml'
                  '''
            }
        }
    }
}