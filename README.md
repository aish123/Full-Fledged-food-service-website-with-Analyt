

Downloading and Installing Node.js:

1) Go to this site http://nodejs.org/dist/latest/ and download the node.js exe file suitable for 

your operating system i.e 32 bit or 64 bit OS.

2) Make a clean directory (preferably in C:)and add that directory to your system's 

PATH variable.

3) Download the latest node.exe to that directory.

4) Download the latest npm's zip file and unpack its contents to the same directory. 

(This is optional step)

Changing systems path environment variable

Right click My computer-> Advance System Settings->Environment Variables->System variables-

>Path

Copy the complete path of the folder containing node.exe and append it to the path variable.

Hello World Example.

Create a sample.js file with code shown below in any directory:

Snippet 1

How to run?? : 

Run->cmd->navigate to the folder containing js file-> and execute “node sample.js”.

Code Explaination :

1: importing the http module and using it in your code through http reference variable.

2: Calling the createServer function of http mode. This returns an object which has function 

called listen and which accepts numeric parameter (port number). Listen function also 

accepts string url as another parameter.

3: The code within the createServer method is an example of function calling another 

function.

The Snippet 1 and 2 both perform same function.

Snippet 2

Hello World Example in Eclipse:

Open Eclipse and go to Help -> Eclipse Market Place -> Type Enide -> Select Enide-Eclipse 

Node.JS IDE 0.8.00 -> Install

And then follow below steps:

Create new project:

New -> Project-> type ‘node’-> Select Node Project -> Finish

Run : Right Click on hello-world-server.js run as node application.

The debugger console shows the server is ready to accept the requests. Hit the url 

http://127.0.0.1:1337/ in the browser.


Adding the code to your system
Install node.js on your laptop and eclipse using the installnode.js pdf.
go to your workspace folder from your git shell and write below command
git clone 
This will create NodeLabTest1 folder in your workspace.
go in that folder and write npm install.
import the project in your eclipse and check if node_modules folder is present.
Now in views folder all your pages are there.
to run the application, just right click on app.js and run as node.js app, then go to browser and type localhost:3000/
Before working go to the project folder from git shell and write git pull.
then after your changes write git add --all
then git commit -m”your message”
git push
this will push your changes to the repository.
