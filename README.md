# ASP.NET-Core---Intermediate-Advanced
Final output from MVA Cource(ASP.NET Core - Intermediate/Advanced) IDE: VSCode

Dependences: Docker for desktop or server.

Commands to up app using PowerShell(fill free for change Docker port):

docker build -t simpleservice .

docker run -d -p 42020:80 simpleservice

URL: http://localhost:42020/api/values

This will only show a property "OSVersion"
