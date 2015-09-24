# SSK1
Base Repository
muleesb API
version: v3
baseUri: https://app.mulesoft.com/api/{version}
/apps: # its fully-resolved URI is https://app.zencoder.com/api/{version}/apps
  displayName: list of mule esb jobs apps
  description: A collection of apps
  /{appId}: # its fully-resolved URI is https://app.zencoder.com/api/{version}/app/{jobId}
    description: A specific app, a member of the apps collection

