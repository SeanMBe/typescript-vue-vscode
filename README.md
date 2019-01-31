# typescript-vue-vscode
Repo for help diagnosing JetBrains WebStorm debugging issue. Sample Vue app for use with vue-clie that is setup for debugging with VSCode. 

Run VS Code
Install VS Code extensions:
1) Vetur
2) Debugger for Chrome

Go to File open Folder and open the root folder that contains the packages.json

Install vue-cli 3.3

(I checked in node_modules, but you can run npm install if you want)

with Node installed go to the folder with packages.json, and run npm serve

In VS Code, open helloworld.vue. You should be able to set a breakpoint in the script section of the file and it should show as red. In VSCode, go Debug -> Start Debugging. Chrome should startup and the sample website load. VS Code should stop at the breakpoint you set.

