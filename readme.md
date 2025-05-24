# nginx config to serve local servers publicly

Remote server running nginx and local server runs the service that needs to be served.

local server connects to remote server through an SSH tunnel to 7575 port.

nginx routes incomming traffic from the domain to port 7575

Set up heavily inspired by https://jerrington.me/posts/2019-01-29-self-hosted-ngrok.html
