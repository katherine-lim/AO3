# Basic How-To

> ### _What is GitHub?_ 
>
> Github is an open source system used to track changes to code and other document files and is free to use.
> Works well with Git, the command line version for GitHub, which is available for Windows, Mac, and Linux. 
> Multiple people can work on the same project or document at the same time with the use of GitHub.
> If needed, creators can revert to previous versions of documents. 

> ### _What is WebStorm?_
>
> WebStorm is an IDE program that can be used to work on code and works well with Java, PHP, or any other coding language.
> The application is easily accessible and free for students and faculty to use to their advantage. 

> ### _How to install Webstorm_
>
> - For starters, navigate to the [Webstorm website](https://www.jetbrains.com/student/ "Webstorm webpage") and register a new account.
> - Then sign up with your school email and head to the [download page](https://git-scm.com/downloads "The download page for WebStorm").
> - Set up the installation to your preferences and download WebStorm. 
> - After Webstorm and GitHub are up and running, we can begin the setup for connecting your GitHub to WebStorm.

> ### _How to setup GitHub_
> 
> - First, open the [GitHub website](https://github.com/join) and open an account.
> - Then download [Git](https://git-scm.com/downloads) on your local system.  

> ### _Connecting WebStorm to Github_
> 
> - With WebStorm open, hit **(Ctr + Alt + S)** to open settings. 
> - On the navigation bar to the left of the settings tab, scroll down to **Version Control** and select _Git_.
> - Open your File Explorer and locate the path to your _git.exe_ from when you downloaded Git.
> - Enter the path to your git.exe into WebStorm.
> - Next, scroll to **Appearance & Behavior > System Settings > Passwords** in the navigation bar in settings and save a password.
> - Open Github, in the upper right-hand corner hit the (+) dropdown icon and create a new repository.
> - Make sure the repository is set to **public** and add a **README.md** file and hit _Create_.
> - Open Webstorm again, and from the menu select click **(Git | Clone)** or if no project is open, click **(Get from VCS)** on the _Welcome_ screen.
> - To import a repository from GitHub:
>>   - In the **Get from Version Control** dialog, specify the URL of the remote repository you want to clone, or select one of the VCS hosting services from the lefthand side
>>   - You can also log in to your GitHub account and link your Webstorm to your GitHub. If you do, it will suggest repositories from your GitHub to connect to WebStorm.
> - Let's test the connection!
>>   - Create a new WebStorm file _(.html or .css)_ on your local system
>>   - A popup should appear asking if you want to add it to GitHub, hit yes.
>>   - Add some code to your new file
>>   - Commit the changes
>>   - Push to your GitHub repository
>>   - Open your GitHub and the new file you created should be there.
> - Next we'll setup GitHub pages:
>>   - Go to the settings tab on your repository
>>   - Select the **master branch**
>>   - Copy the new URL generated into a new and you have your new link

> ### _Terms to Know_
> - ***Branch*** \
>     A sub section of your repository 

