withCredentials([azureServicePrincipal('AzureServicePrincipal')]) {
    sh 'az login --service-principal -u $AZURE_CLIENT_ID -p $AZURE_CLIENT_SECRET -t $AZURE_TENANT_ID'
}
