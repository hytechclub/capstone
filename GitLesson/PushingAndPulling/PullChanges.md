# Pull Changes
When you want to retrieve changes from the server, you will have to **pull** those changes down. You can pull changes from a personal or team GitHub repository.

## Pulling Changes in Visual Studio Code
Visual Studio Code has an interesting tool for pulling changes down from the remote repository. Instead of simply pulling changes, it actually _synchronizes_ the local and remote repositories. This means that it pushes any commit changes up, and also pulls down any changes from the server that may exist.

To pull your changes down, use the **Synchronize Changes** button on the blue bar at the bottom of the window:  
![](https://i.imgur.com/d2PY1qT.png)

Once you click that button, your server changes should exist in your local clone! You can go to your repository on GitHub and make sure it matches your local repository.

## Pulling Changes in Visual Studio
Visual Studio has some nice built-in tools for pulling changes from the remote repository.

1. Open the **Team Explorer** pane  
    ![](https://i.imgur.com/TIRIdPc.png)
1. Under "Project", click **Sync**  
    ![](https://i.imgur.com/GhmxHki.png)
1. Under "Incoming Commits", click **Pull**  
    ![](https://i.imgur.com/P6LYa3u.png)
    - _Note: To simply view incoming commits, but not merge them, you can click **Fetch**_

Once you pull, your server changes should exist in your local clone! You can go to your repository on GitHub and make sure it matches your local repository.

## Pulling Changes via the Command Line
If you're using the command line, pulling from your server repository is simple:

1. Change your directory to the folder that contains your repository (replace `/path/to/repository/` with your path) 
    ```bash
    cd /path/to/repository/
    ```
1. Run the `pull` command
    ```bash
    git pull
    ```

That's it! Now your local clone repository should have all the latest changes from your GitHub repository.