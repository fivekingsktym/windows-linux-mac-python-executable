# Windows-Linux-Mac-Python-Executable

When executing Python code as "python create.py projectname" becomes tedious, follow these pro tips to streamline your workflow with "create projectname".

## Windows Setup:

- #### Make the script executable:

- Set up your "Environment Variable" in Windows, so that you can run the script from any path:

    - How to Set up Environment Variable:
        - Open System Properties (you can do this by right-clicking on "This PC" or "Computer" on the desktop or in File Explorer, then selecting "Properties").
        - Click on "Advanced system settings".
        - Click on the "Environment Variables" button.
        - In the "System variables" section, find the Path variable, select it, and click "Edit".
        - Click "New" and add the path to your script's directory.
        - Click "OK" to close all dialog boxes.

- Run the script [Now you can run from any path]:
    ```bash
    create projectname
    ```

- If `create projectname` does not work, close the terminal and open a new one, then try again!



## Linux and Mac Setup:-

#### Make the script executable: 

- Open a terminal in "/your/workspace/django_automation/" and run the script below.

```bash
chmod +x ./scripts/create.sh
```

[ Note: You must be in the "django_automation" path for this to work. Otherwise, it will not work. You need to perform this task outside of the "django_automation" path, and you need to specify the complete path! ]

- Configure Environment Variable, enabling script execution from any path:
  - Copy the script to a directory in PATH: "/your/workspace/django_automation/"
    ```bash
    sudo cp ./scripts/create.sh /usr/local/bin/
    ```

- Run the script [Now you can run from any path]:
    ```bash
    create projectname
    ```

- If `create projectname` does not work, close the terminal and open a new one, then try again!
