pipeline {
    agent any
    
    stages {
        stage('echo') {
            steps {
                echo "TARGET_NAMESPACE=${TARGET_NAMESPACE}"
                //sh('oc -n ${TARGET_NAMESPACE} new-app jboss-eap72-openshift:latest~https://github.com/RedHatTraining/DO288-apps.git --context-dir=java-serverhost ')
            }
        }
    }
}
