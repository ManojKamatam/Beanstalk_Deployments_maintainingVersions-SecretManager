# Beanstalk_Deployments_maintainingVersions-SecretManager

if def credentials = readJSON text: secretValue is being used to retriew secret manager: Then please install

# Pipeline Utility Steps

Without any pipeline just use 

# groovy.json.JsonSlurper

If secret manager is not stored in form of json, then

# def secretParts = secretValue.split('\n')
                    env.AWS_ACCESS_KEY_ID = secretParts[0].trim()
                    env.AWS_SECRET_ACCESS_KEY = secretParts[1].trim()
