Follow steps here:
https://learn.microsoft.com/en-us/azure/data-api-builder/command-line/install

Prerequisite is .NET 8 with aspnetcore runtime

start dab
dab start -c ./dab/dab.config.json

test with swagger
http://127.0.0.1:5000/swagger/index.html

leave dab running. 
start another terminal

We are now using this:
https://learn.microsoft.com/en-us/azure/static-web-apps/apis-container-apps 

Set up container
https://learn.microsoft.com/en-us/azure/data-api-builder/deployment/how-to-publish-container-apps#build-the-configuration-file 