# AI Startup Website Repository

This repository contains the basic HTML structure for the AI startup website, as outlined previously.

## Getting Started

Follow these steps to get a local copy of the project up and running and contribute to the `update-navigation` branch.

### Prerequisites

* Git installed on your system.
* Visual Studio Code (VS Code) or another code editor with a terminal.

### Cloning the Repository

1.  Open your terminal in VS Code (or your preferred terminal).
2.  Navigate to the directory where you want to clone the repository.
3.  Run the following command:

    ```bash
    git clone https://github.com/onojaonoja2/3mtt_DevOps/tree/main/ai_startup.git
    ```

    

    ![Git Clone Command](./img/git_clone.png)
    *Screenshot of the `git clone` command in the VS Code terminal.*

### Ensuring Your Local Repository is Up-to-Date

1.  Once the repository is cloned, navigate into the project directory:

    ```bash
    cd ai_startup
    ```

2.  Before making changes, it's a good practice to ensure your local `main` (or `master`) branch is up-to-date with the remote repository. Switch to the `main` branch:

    ```bash
    git checkout main
    ```

3.  Then, pull the latest changes:

    ```bash
    git pull origin main
    ```

    ![Git Pull Command](./img/git_pull.png)
    *Screenshot of the `git pull` command in the terminal.*

### Switching to the `update-navigation` Branch

1.  Now, switch to the `update-navigation` branch to work on the navigation updates:

    ```bash
    git checkout update-navigation
    ```

    ![Git Checkout Update-Navigation Command](./img/git_checkout_update-navigation.png)
    *Screenshot of the `git checkout update-navigation` command in the terminal.*

### Making Changes and Pushing to the Remote Repository

1.  Make your changes to the `index.html` file (or any other relevant files).
2.  Stage your changes:

    ```bash
    git add .
    ```

3.  Commit your changes with a descriptive message:

    ```bash
    git commit -m "Update navigation links and structure"
    ```

4.  Finally, push your local `update-navigation` branch to the remote repository:

    ```bash
    git push origin update-navigation
    ```

    ![Git Push Command](./img/git_push.png)
    *Screenshot of the `git push` command in the terminal.*

