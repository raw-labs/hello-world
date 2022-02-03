# hello-world
# 

## Run RAW Hello world!

By following the steps here after you should be able to run the basic Hello World! app in RAW.

1. RAW account<p>
To run this app, you need to be registered on raw-labs.com
2. Visual Studio Code<p>
In VS code, search for the RAW Labs extension in the standard Marketplace and install it.<p>
https://marketplace.visualstudio.com/items?itemName=RAWLabs.raw
3. GitHub<p>
Log into your GitHub account and install the RAW repository reader app. This application will synchronise your code with the RAW execution servers<p>
https://github.com/apps/raw-repository-reader
4. Clone this repository<p>
Clone this repository with your favorite CLI tool or with the VS Code Git extension. 
5. Connect to the execution server and verify it works correclty<p>
Select the RAW Labs extension on the left menu bar in vS code and choose the Scratchpad option at the top right.

![VS Code menus](images/screen1.png)

6. Run the test code
In the scratchpad window, on the top right, there is a green "Run" arrow. Click it to run the test code in the scratchpad.<p>
It should ask you for a token from the execution server.<p>
7. Get the RAW token
Go to the RAW Labs admin console and get the token from the top right user's menu.<p>
![Token from the RAW admin console](images/token1.png)
Copy the token and enter it in VS Code when asked to.<p>
This will connect your IDE with the RAW execution server.<p>
You should now see the basic test code output on a JSON output tab<p>
8. Execute Hello World!
In the RAW Extension file explorer, select the hellow-world.yml file and then on the green right arrow to run the file.<p>
9. Commit the Hello-world app to your own GitHub repo
By doing so, the hello-world endpoint will become live from your published URL (hello-world in your raw-site.yml file)<p>
10. Check if the app is up and running
Go to the RAW admin console, you should see the hello-world repo in the repository menu and the corresponding enpoints in the catalog menu.<p>
From the catalog menu, you can copy the URL endpoint to your browser address bar and verify that it is working. 



Endpoints :
## hello-world
hello-world

https://api.raw-labs.com/hello-world/hello-world

## hello-name
hello-name(name: string)<p>
returns "Hello `name`!"

https://api.raw-labs.com/hello-world/hello-name?name=Joe

