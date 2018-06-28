# node-application-server
a node based application server with interface to start stop and restart apps and dynamically or statically assign port # and database path.

# goals
- create server that automatically runs on hardware startup.
- allow server access to start stop and restart another self contained application.
 - I do not want the apps to be customized to only work in this server, I want ordinary apps to run in this server.
- allow app to modify app's .env file in order to customize port and database settings.