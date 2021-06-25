# Create and Clone a Repository
The first step to make a project in GitHub is to create and clone a GitHub Repository. Make sure to log into your GitHub account and verify your email before getting started.

## Creating Your Own Repository
If you do not want to use an existing repository, you can create a totally new one! In GitHub, click the _plus_ icon in the upper right, and select New Repository:  
![](https://i.imgur.com/nYm5RJh.png)

Fill out some information, and you'll have your own repository!

## Downloading and Installing Git
In order to actually clone a GitHub Repository locally, it will be necessary to download and install Git.

- On a Mac or Linux machine, download Git from here: https://git-scm.com/downloads
- On a Windows machine, download Git from here: https://gitforwindows.org/
    - This comes with Git BASH, a command-line utility

## Cloning the Repository
Once you have everything downloaded and installed, you can clone your repository on your local machine to play around with it!  A **clone** is a copy of a repository that lives on your computer instead of on a website's server somewhere.

1. On the right side of your repository page, click the **Clone or download** button
    - Make sure you are on the **Clone with HTTPS** menu
1. Click the _copy_ icon to copy your repository URL to your clipboard  
    ![](https://i.imgur.com/D1iXTDp.png)

Depending on which tool you are using, follow the instructions in one of the sections below to complete the cloning process.

### Cloning in Visual Studio Code
If you have installed Git on your machine, Visual Studio Code has built-in Git tools you can use.

1. Open Visual Studio Code
1. Press `Ctrl`+`Shift`+`P` to open the Command Palette
1. Type in ">Git: Clone" and press `Enter` to execute the command  
    ![](https://i.imgur.com/WEoYQer.png)
1. Paste in your repository URL and press `Enter` to confirm  
    ![](https://i.imgur.com/UZHIFN0.png)
1. Navigate to a suitable location for your repository folder, and click the **Select Repository Location** button  
    ![](https://i.imgur.com/ELgHyHy.png)
1. Once your repository is cloned, a popup should appear in the lower right corner of the window. Click the **Open Repository** button to open a new instance of VS Code with the newly cloned repository
    ![](https://i.imgur.com/rKdgz2p.png)

### Cloning in Visual Studio
If you have Git installed on your machine, Visual Studio has built-in Git tools you can use.

1. Open Visual Studio
1. Open the **Team Explorer** pane  
    ![](https://i.imgur.com/TIRIdPc.png)
1. Click the _Manage Connections_ icon (plug)  
    ![](https://i.imgur.com/jOUjiQY.png)
1. Under "Hosted Service Providers", find "GitHub" and click **Connect**  
    ![](https://i.imgur.com/3VvhShx.png)
1. In the window that pops up, enter your credentials and click **Sign in**  
    ![](https://i.imgur.com/3DrwOTR.png)
1. Under "GitHub", click **Clone**  
    ![](https://i.imgur.com/FpDvXrq.png)
1. In the window that pops up, select the repository you wish to clone
1. Click **Browse** to find a proper folder in which to clone the repository
1. Click **Clone** to begin the cloning process  
    ![](https://i.imgur.com/vc1k5M6.png)

### Cloning via the Command Line
If you have Git Bash installed on your machine (or another shell), you can use that for all Git commands.

1. Open your shell application (e.g. Git Bash)
1. Change your directory to wherever you'd like the repository to live
    ```bash
    cd /path/to/folder/
    ```
1. Use the `clone` command to clone the repository (paste in the repository's url after `clone`)
    ```bash
    git clone https://github.com/YOUR_REPO_URL.git
    ```

That's it! Now you have a local clone of your repository.