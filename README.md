[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15292419&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.

a. Go to your browser and type 'Visual studio code download' ensure you have a stable internet connection.
b. Open the official site of the Visual studio code site and you will see three download options; windows, Mac and Linux.
c. Since we are using windows, choose the windows option.
d. This will initiate the download process
e. After the down load is complete, click on it to install it locally on your system.
f. The set up wizard will appear, accept the terms and proceed with the set up then install.
e. Finish the installation, you can launch and explore the Visual studio code.


2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.

   After installing the VS code interface, you can explore the extentions button and install other extensions that will be useful to your specialization and support your development workflow. For example, you can install Python, Pylance, Prettier etc.
   You can also change the theme on the settings buttons. You can also explore install features that give you a variety of fonts and colors for your codes on the extentions icon.

3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.

   a. Activity Bar - Located on the far left-hand side. Lets you switch between views and gives you additional context-specific indicators, like the number of outgoing changes when Git is enabled. You can change the position of the Activity Bar.
   
   b.Side Bar - Contains different views like the Explorer to assist you while working on your project.

   c. Editor group - The main area to edit your files. You can open as many editors as you like side by side vertically and horizontally.
   
   d. Status Bar - Information about the opened projects and files that you are currently editing


4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.

   The command palette can ve accessed on the VS code by pressing ctrl+Shift+P. From here, you can access all functionalities within the VS code including keyboard shortcuts and most common operations.The Command Palette provides access to many commands. You can run editor commands, open files, search for symbols, and see a quick outline of a file, all using the same interactive window. 

5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.
 
   VS Code extensions let you add languages, debuggers, and tools to your installation to support your development workflow. You can browse and install extensions from within VS Code. Bring up the Extensions view by clicking on the extensions icon in the Activity Bar on the side of VS Code or the View: Extensions command (Ctrl+Shift+X).
   Web developers can install the Live server extension for VS code which starts a local server that serves pages using the contents of files in the workspace. The server will automatically reload when an associated file is changed.


6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?

You can open the integrated terminal in VS code from the menu, use the Terminal > New Terminal or View > Terminal menu commands. You can have terminal editors on either side or arranged in multiple dimensions using the editor group layout system, e.g. PowerShell and WSL terminals stacked to the right of file editors.
The integrated terminal can use various shells installed on your machine, with the default being pulled from your system defaults. Shells are detected and presented in the terminal profiles dropdown.



7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?

   The Explorer view is used to browse, open, and manage the files and folders in your project. VS Code is file and folder based and you can get started immediately by opening a file or folder in VS Code.
   After you open a folder in VS Code, the contents of the folder are shown in the Explorer view. You can do many things from here:
        a. Create, delete, and rename files and folders.
        b. Move files and folders with drag and drop.
        c.Use the context menu to explore all options.


8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.

   When you click on the settings icon, two scopes of settings options are displayed; 
   a. User settings - Settings that apply globally to any instance of VS Code you open.
   b. Workspace settings - Settings stored inside your workspace and only apply when the workspace is opened.
   You will find the option for changing the theme, font size and keybindings on the user settings under the text editors.

9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?

- To bring up the Run and Debug view, select the Run and Debug icon in the Activity Bar on the side of VS Code. You can also use the keyboard shortcut Ctrl+Shift+D. 
- The Run and Debug view displays all information related to running and debugging and has a top bar with debugging commands and configuration settings.
- VS Code has built-in debugging support for the Node.js runtime and can debug JavaScript, TypeScript, or any other language that gets transpiled to JavaScript.
- In addition to debugging a program, VS code supports running the program.


10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.

    a. Sign into VS Code with your GitHub account in the Accounts menu in the lower right of the Activity bar to enable additional features like Settings Sync, but also cloning and publishing repositories from GitHub.
    b. If you clone from GitHub, VS Code prompts you to authenticate with GitHub. Then, select a repository from the list to clone to your machine. The list contains both public and private repositories.
    To initialize a new local Git repository:
       - Pick an existing or new folder on your computer and open it in VS Code
       - In the Source Control view, select the Initialize Repository button
       - This creates a new Git repository in the current folder, allowing you to start tracking code changes
       - Use the Publish to GitHub command button in the Source Control view. You can then choose a name and description for the repository, and whether to make it public or private.


REF Article: https://code.visualstudio.com/docs/sourcecontrol/intro-to-git


 
 
Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

