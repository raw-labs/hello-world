# hello-world
# 

## Run RAW Hello world!

By following the steps here after you should be able to run the basic Hello World! app in RAW.

1. RAW account<br>
To run this app, you need to be registered on raw-labs.com<br><br>
2. Visual Studio Code<br>
In VS Code, search for the RAW Labs extension in the standard Marketplace and install it.<br>
https://marketplace.visualstudio.com/items?itemName=RAWLabs.raw<br><br>
3. Clone this repository<br>
Clone this repository with your favorite CLI tool or with the VS Code Git extension.<br><br> 
4. GitHub<br>
Log into your GitHub account, create a remote repository for the Hello World project, connect your local folder to the remote and commit there (more instructions [here](https://docs.github.com/en/get-started/importing-your-projects-to-github/importing-source-code-to-github/adding-an-existing-project-to-github-using-the-command-line) ).<br>
For RAW labs to be aware of the code you want to run, you need to install the RAW repository reader app. This application will synchronise your code with the RAW execution servers<br>
Go [there](https://github.com/apps/raw-repository-reader) and select your remote Hello World repository to allow RAW to access it<br>
<p align="center">
  <img src="images/screen2.png" alt="Repository access"/>
</p>
5. In VS Code, connect to the execution server and verify it works correclty.<br>
Select the RAW Labs extension on the left menu bar in VS Code and choose the Scratchpad option at the top right.<br>
<br>
<p align="center">
  <img src="images/screen1.png" alt="VS Code menus"/>
</p>
<br>
6. Run the test code
In the scratchpad window, on the top right, there is a green "Run" arrow. Click it to run the test code in the scratchpad.<br>
It should ask you for a token from the execution server.<br><br>
7. Get the RAW token<br>
Go to the [RAW admin console](https://app.raw-labs.com/) and get the token from the top right user's menu.<br>
<br>
<p align="center">
  <img src="images/token1.png" alt="Token from the RAW admin console"/>
</p>
Copy the token and paste it in VS Code when asked to.<br>
This will connect your IDE with the RAW execution server.<br>
You should now see the basic test code output on a JSON output tab<br><br>
8. Execute Hello World!<br>
In the RAW Extension file explorer, select the hellow-world.yml file and then on the green right arrow to run the file.<br><br>
10. Check if the app is up and running<br>
Go to the [RAW admin console](https://app.raw-labs.com), you should see hello-world in the repository menu and the corresponding enpoints in the catalog menu.<br><br>
From the catalog menu, you can copy the URL endpoint to your browser address bar and verify that it is working.<br>
It should be in this format https://`your-domain`.raw-labs.com/`publishUrl`/hello-world<br>
<br>


Endpoints :
## hello-world
hello-world

https://api.raw-labs.com/hello-world/hello-world

## hello-name
hello-name(name: string)<br>
returns "Hello `name`!"

https://api.raw-labs.com/hello-world/hello-name?name=Joe

