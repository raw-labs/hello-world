
## Get Started with RAW: Hello world!

It's easy, follow these steps to get going with RAW.<br>

If you get stuck, watch our video (4 mins):

[![Get Started with RAW: Hello World](https://img.youtube.com/vi/Viz59fhlET4/0.jpg)](https://www.youtube.com/watch?v=Viz59fhlET4)


## Pre-requisites
- GitHub account (personal one is fine)
- [Download and install](https://code.visualstudio.com/download) VS Code
- RAW id - to request access, email us at hello@raw-labs.com or go to our [website](https://raw-labs.com#subscribe) and register. We will set you up with an Organization Name, and send this to your email. 


### 1. GitHub 
see on [YouTube](https://www.youtube.com/watch?v=Viz59fhlET4&t=19s)
- Log into your GitHub account, and Fork this [hello-world](https://github.com/raw-labs/hello-world) repository (top right) to your account<br>
- RAW needs access to your new repository in order to synchronize and execute code. Go to our [Repository Reader](https://github.com/apps/raw-repository-reader) GitHub app, Click Configure and select your GitHub Account, then the repository you just created, to allow RAW to access it. (You can also give RAW access to all, or multiple repositories)<br>
- To Develop locally, clone your new forked repository, either in GitHub Deskop, command-line, or do it below in VS Code if you prefer<br>


### 2. RAW App
see on [YouTube](https://www.youtube.com/watch?v=Viz59fhlET4&t=61s)
- Login to the [RAW App](https://app.raw-labs.com), and enter your Organization Name, and click "Administration"<br>

- It will prompt you for email and password, but click _'Don't Remember Your Password'_<br>

- You will receive an email to **reset your password** - click on that and set your password
- Once logged into the RAW App, click on your email account from the top right corner menu and **copy the token**  (you will need it later for VS Code).<br>


### 3. VS Code
see on [YouTube](https://www.youtube.com/watch?v=Viz59fhlET4&t=117s). Also, full instructions for the VS Code extension can be found [here](https://github.com/raw-labs/vscode/blob/main/README.md)
- In VS Code, search for the RAW Labs extension in the standard Marketplace and install it. You can find it [here](https://marketplace.visualstudio.com/items?itemName=RAWLabs.raw) too. 

- Clone the new repository if you haven't alraeady, in VS Code (you will need a [GitHub Extension](https://marketplace.visualstudio.com/search?term=Github&target=VSCode&category=All%20categories&sortBy=Installs))<br>

- Click on the RAW Labs extension on the left side bar, and navigate to 'hello-world.yml' in the RAW File Explorer (top left). Click on the Green 'run' arrow. You will be prompted to authenticate, click Allow, and then paste your Personal Access Token that you copied earlier at the top of the screen and hit Enter. The "Hello World!" message should now appear in an output window.<br>

- There is also a Scratchpad, you can enter commands here and click green 'run' arrow on the top right of the scratchpad window. This is where you can develop your own code.<br>

- Click on the 'hello-name.yml' file in the RAW File Explorer. This endpoint requires a parameter. Underneath the File Explorer there is a 'Test YAML Arguments' area. Click on 'Add Arguments Set'. Check 'Argument Set 0' and enter 'name' and 'yourname'. Now click on the 'run' arrow next to 'hello-name.yml'. The output should read accordingly using 'Hello <yourname>!"<br>


### That's it! You're set up :-)

You can now go back to the RAW App, click 'Refresh' in the Catalog, and see the endpoints in the same path as your Git Repository, and the Repositories with main branch showing Active<br>


From the catalog menu, you can copy the URL endpoint for either 'hello-world' or 'hello-name' endpoints to your browser address bar and verify they are working.
Endpoints will be named 'yourOrganization' instead of 'api'<br>


## hello-world
hello-world()<br>
returns "Hello World!"

https://api.raw-labs.com/hello-world/hello-world

## hello-name
hello-name(name: string)<br>
returns "Hello `name`!"

https://api.raw-labs.com/hello-world/hello-name?name=Joe



