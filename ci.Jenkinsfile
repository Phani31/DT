@Library("ci@master") _

NodeAppPublish(
    'nodeVersion': '18.20.3',
    'compileScriptPath': 'compile.sh',
    'buildFolder': 'dist',
    'tenant': 'omega',
    'bucketsToPush': ['aws:31051:zetaapps-artifacts'],
    'enableCodeSonarSastScan': false,
    'enableCodeSonarSastGating': false,
    'enableCodeSonarUTRun': false,
    'disablePushToJfrog': true,
    'timeout': 30
)