[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15256165&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.


 Steps to Download and Install Visual Studio Code
 * Download Visual Studio Code
    1. Open a Web Browser: Open your preferred web browser (e.g., Chrome, Edge, Firefox).
    2. Navigate to the VS Code Website: Go to the official Visual Studio Code download page: https://code.visualstudio.com/.
    3. Download the Installer: Click on the "Download for Windows" button. This will download the VS Code installer (a .exe file).
 * Install Visual Studio Code
    1. Run the Installer: Locate the downloaded VSCodeUserSetup-x64-<version>.exe file in your Downloads folder and double-click it to start the installation process.
    2. Accept the License Agreement: Read through the license agreement and click "I accept the agreement" if you agree. Then, click "Next."
    3. Choose Install Location: Select the destination folder where you want to install VS Code. The default location is usually fine. Click "Next."
    4. Select Additional Tasks: Choose any additional tasks you want the installer to perform. Common options include:
        ◦ Create a desktop icon
        ◦ Add "Open with Code" action to Windows Explorer file context menu
        ◦ Add "Open with Code" action to Windows Explorer directory context menu
        ◦ Register Code as an editor for supported file types
        ◦ Add to PATH (this is very useful as it allows you to open the terminal and type code to launch VS Code)
       Select the options you prefer and click "Next."
    5. Install VS Code: Click "Install" to begin the installation process. This might take a few minutes.
    6. Launch VS Code: After the installation is complete, you can choose to launch VS Code immediately by checking the "Launch Visual Studio Code" box and clicking "Finish."


2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.

    1. Theme and Appearance
    • Color Theme: Go to File -> Preferences -> Color Theme (or Ctrl+K, Ctrl+T) and choose a theme you like. Popular themes include Dark+ (default dark) and Light+ (default light).
    • Icon Theme: Go to File -> Preferences -> File Icon Theme and select an icon theme. 
    Recommended Extensions
    2. Language Support
        ◦ Python: Install the Python extension by Microsoft for Python development, which includes IntelliSense, linting, debugging, and more.
        ◦ JavaScript/TypeScript: Built-in support, but consider installing ESLint and Prettier - Code formatter for better linting and formatting.
        ◦MySQL
        ◦Flutter and Dart
        ◦Django


3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.

 Visual Studio Code (VS Code) has a user interface that is designed to be intuitive and customizable, making it easier for developers to navigate and use. Here are the main components of the VS Code user interface, including the Activity Bar, Side Bar, Editor Group, and Status Bar:
 * Activity Bar
 Location: Left side of the window
 Purpose: The Activity Bar allows you to switch between different views and provides quick access to core functionalities. Each icon in the Activity Bar represents a different view or extension.
 Key Icons and Their Functions:
    • Explorer: (Files icon) Shows the file and folder structure of your project.
    • Search: (Magnifying glass icon) Allows you to search for text in your files.
    • Source Control: (Branch icon) Provides access to version control features, such as Git.
    • Run and Debug: (Play icon) Enables you to run and debug your applications.
    • Extensions: (Square icon) Allows you to browse and install VS Code extensions.
    • Remote: (If you have remote extensions installed) Access remote development features.
 * . Side Bar
 Location: To the right of the Activity Bar
 Purpose: The Side Bar displays the contents of the selected view from the Activity Bar. It provides detailed information and interactions related to the selected view or extension.
 Common Views:
    • Explorer View: Shows your project's directory structure, allowing you to open, rename, delete, and manage files and folders.
    • Source Control View: Displays your version control information, including changes, branches, and commit history.
    • Extensions View: Lists installed extensions and allows you to search for and install new extensions.
    • Debug View: Displays debug-related information, such as breakpoints, variables, and the call stack.
 * . Editor Group
 Location: Center of the window
 Purpose: The Editor Group is where you open and edit your files. It supports multiple editors in a tabbed interface and allows you to split the view to compare or work on multiple files side-by-side.
 Key Features:
    • Tabs: Each open file appears as a tab at the top of the Editor Group. You can switch between tabs, close them, or drag them to reorder.
    • Split Editor: You can split the editor horizontally or vertically to view multiple files simultaneously. Use the split editor icon in the top-right corner of the editor or right-click on a tab and choose "Split Right" or "Split Down."
    • Minimap: A small overview of your code, displayed on the right side of the editor, allowing for quick navigation within a file.
    • Code Folding: Collapse and expand code sections to improve readability and focus on specific parts of the code.
 * . Status Bar
 Location: Bottom of the window
 Purpose: The Status Bar provides information about the current state of your workspace, open files, and various settings. It also offers shortcuts to perform common tasks.
 Key Information and Features:
    • Language Mode: Shows the current language mode (e.g., Python, JavaScript). Clicking on it allows you to change the language mode.
    • Line and Column Numbers: Indicates the current cursor position in terms of line and column number.
    • Encoding: Shows the file encoding (e.g., UTF-8). Clicking on it allows you to change the encoding.
    • EOL (End of Line) Sequence: Displays the line-ending style (e.g., LF, CRLF). Clicking on it allows you to change the EOL sequence.
    • Indentation: Displays the current indentation size and type (spaces or tabs). Clicking on it allows you to change the indentation settings.
    • Git Branch and Sync Status: Shows the current Git branch and indicates if there are changes to sync. Clicking on it opens the Source Control view.
    • Notifications and Problems: Displays icons for errors, warnings, and other notifications. Clicking on these icons opens the Problems view.


4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.


 The Command Palette in Visual Studio Code (VS Code) is a powerful feature that provides quick access to a wide range of commands and settings. It allows you to perform tasks without navigating through menus and can be a huge productivity boost.
 Accessing the Command Palette
 You can access the Command Palette by using the keyboard shortcut or through the menu:
    • Keyboard Shortcut: Ctrl+Shift+P (Windows/Linux) or Cmd+Shift+P (Mac)
    • Menu: Go to View -> Command Palette...
 Using the Command Palette
 When you open the Command Palette, a text box appears at the top of the VS Code window where you can type commands. As you type, VS Code provides suggestions and matches based on what you’ve entered.
 Common Tasks Performed Using the Command Palette
 Here are some examples of tasks you can perform using the Command Palette:
   * Changing Color Theme
        ◦ Open the Command Palette: Ctrl+Shift+P
        ◦ Type: Theme:
        ◦ Select: Preferences: Color Theme
        ◦ Choose a theme from the list.
   * Installing Extensions
        ◦ Open the Command Palette: Ctrl+Shift+P
        ◦ Type: Install Extensions
        ◦ Select: Extensions: Install Extensions
        ◦ Search for and install the desired extension.
   * Running a Task
        ◦ Open the Command Palette: Ctrl+Shift+P
        ◦ Type: Run Task
        ◦ Select: Tasks: Run Task
        ◦ Choose a task from the list (e.g., build, test).
   * Opening Settings
        ◦ Open the Command Palette: Ctrl+Shift+P
        ◦ Type: Preferences: Open Settings (UI) or Preferences: Open Settings (JSON)
   * Navigating to a File
        ◦ Open the Command Palette: Ctrl+P
        ◦ Type the name of the file you want to open.
   * Formatting Code
        ◦ Open the Command Palette: Ctrl+Shift+P
        ◦ Type: Format Document
        ◦ Select the command to format the current file.
   * Git Commands
        ◦ Open the Command Palette: Ctrl+Shift+P
        ◦ Type: Git:
        ◦ Access various Git commands like Git: Commit, Git: Push, Git: Pull, etc.
   * Executing a Debug Command
        ◦ Open the Command Palette: Ctrl+Shift+P
        ◦ Type: Debug:
        ◦ Access debug commands like Debug: Start Debugging, Debug: Add Configuration, etc.
   *  Opening a Terminal
        ◦ Open the Command Palette: Ctrl+Shift+P
        ◦ Type: Terminal:
        ◦ Select Terminal: Create New Integrated Terminal to open a new terminal.
   * Toggling Sidebar Visibility
        ◦ Open the Command Palette: Ctrl+Shift+P
        ◦ Type: View: Toggle Side Bar Visibility
        ◦ Select the command to show or hide the Side Bar.


5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.

  Role of Extensions in VS Code
    * Language Support: Extensions provide support for programming languages not natively supported by VS Code, including syntax highlighting, IntelliSense, and debugging capabilities.
    * Productivity Enhancements: Extensions can improve workflow and productivity with features like snippets, code formatting, linting, and task automation.
    * . Tool Integration: Extensions allow seamless integration with version control systems, build tools, deployment pipelines, and cloud services.
    * . Customization: Users can tailor the editor's appearance and behavior through themes, icons, and UI customization extensions.
    * . Debugging: Extensions provide advanced debugging tools and features for various languages and frameworks.
 Finding, Installing, and Managing Extensions
 Finding Extensions
   * Extensions View: Click the Extensions icon in the Activity Bar on the side of the window or use the shortcut Ctrl+Shift+X.
   * Search Bar: Use the search bar in the Extensions view to find extensions by name, category, or keyword.
 Installing Extensions
   * Extensions View: After finding the desired extension, click the Install button next to it.
   * Command Palette: Open the Command Palette (Ctrl+Shift+P), type Extensions: Install Extensions, and search for the extension you want to install.

   Managing Extensions
    * Enable/Disable Extensions: Right-click on the extension in the Extensions view and select Enable or Disable.
    * Update Extensions: Extensions can be updated from the Extensions view by clicking the update button if available.
    * Uninstall Extensions: Right-click on the extension in the Extensions view and select Uninstall.
    * Extension Settings: Some extensions have configurable settings accessible via File -> Preferences -> Settings or by clicking the gear icon next to the extension in the Extensions view.
   
   Here are some popular and essential extensions for web development:
   * HTML, CSS, and JavaScript
    • HTML CSS Support: Provides CSS class and id validation in HTML files.
    • Prettier - Code Formatter: Automatically formats code to ensure a consistent style across HTML, CSS, JavaScript, and other supported languages.
    • ESLint: Integrates ESLint into VS Code for identifying and reporting on patterns found in JavaScript/TypeScript code.
    • Live Server: Launches a local development server with live reload feature for static and dynamic pages.
   * Frameworks and Libraries
    • React Native Tools: Provides a debugging environment for React Native projects.
    • Vue.js Extension Pack: A collection of extensions to support Vue.js development, including Vetur for Vue-specific features.
    • Angular Essentials: An extension pack for Angular development, including Angular Language Service, Snippets, and CLI integration.
   * Version Control
    • GitLens: Enhances the built-in Git capabilities with features like blame annotations, repository explorer, and more.
    • Git Graph: Visualize your repository’s commit history in a graph format.
   * Productivity Tools
    • Path Intellisense: Autocompletes filenames as you type.
    • Bracket Pair Colorizer 2: Colors matching brackets to make nested code easier to read.
    • Auto Rename Tag: Automatically renames paired HTML/XML tags.
   * Debugging
    • Debugger for Chrome: Debug JavaScript code in the Google Chrome browser, or other targets that support the Chrome Debugging Protocol.
    • Debugger for Firefox: Debug JavaScript code in the Mozilla Firefox browser.
   * Terminal Integration
    • Terminal: Integrated terminal allows you to run shell commands within VS Code without switching context.


6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?

- Opening and Using the Integrated Terminal
    1. Keyboard Shortcut:
        ◦ Windows/Linux: Ctrl + (Ctrl + backtick)
        ◦ Mac: Cmd + (Cmd + backtick)
    2. Menu Navigation:
        ◦ Go to View -> Terminal.
    3. Command Palette:
        ◦ Open the Command Palette (Ctrl + Shift + P or Cmd + Shift + P).
        ◦ Type Terminal: Create New Integrated Terminal and select it.
- Using the Integrated Terminal
Once the terminal is open, it appears at the bottom of the VS Code window. You can use it just like any other terminal. Here are some common tasks you can perform:
   1. Running Commands: You can run shell commands, scripts, and executables just as you would in a regular terminal.
      
   2. Multiple Terminals: You can open multiple terminal instances. Click the + icon in the terminal tab bar or use the Command Palette to create a new terminal.
        ◦ Keyboard Shortcut: Ctrl + Shift + (Windows/Linux) or Cmd + Shift + (Mac).
   3. Switching Terminals: Use the dropdown menu in the terminal tab bar to switch between open terminals.
   4. Splitting Terminals: You can split the terminal view to run commands side by side.
        ◦ Click the split terminal icon (two overlapping squares) or right-click on the terminal tab and select Split Terminal.
   5. Customizing Terminal Settings:
        ◦ Go to File -> Preferences -> Settings.
        ◦ Search for terminal to customize various settings such as font size, shell integration, and more.
- Advantages of Using the Integrated Terminal
    1. Seamless Workflow: The integrated terminal allows you to stay within the VS Code environment, reducing context switching and improving productivity. You can quickly run commands related to your code without leaving the editor.
    2. Synchronization with the Editor: The integrated terminal opens in the context of the current project workspace, so file paths and environment settings are automatically aligned with your project's configuration.
    3. Enhanced Productivity:
        ◦ Task Integration: You can run predefined tasks directly from the terminal or configure tasks that can be executed with a single command.
        ◦ Shortcuts and Commands: Quickly execute commands using VS Code shortcuts, reducing the need to remember long command sequences.
    4. Multiple Terminals: Easily manage multiple terminal instances within the same window. This is useful for running different commands simultaneously, such as running a development server and a build process.
    5. Customization: The integrated terminal can be customized to match your preferences, including shell type (e.g., bash, zsh, PowerShell), themes, and keybindings.
    6. Extension Integration: Extensions can enhance the functionality of the integrated terminal, such as adding command snippets, improving shell integration, and providing additional tools.
    7. Platform Consistency: The terminal works consistently across different operating systems (Windows, macOS, Linux), providing a unified experience regardless of the platform.
- Example Usage Scenario
    • Web Development: Open a terminal to run npm start to launch a development server, another terminal to watch for file changes with npm run watch, and a third to run tests with npm test.
    • Version Control: Use one terminal for running Git commands to manage your repository while coding in the editor.
    • Automation: Run build scripts, deployment scripts, or other automation tasks directly from the integrated terminal.


7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?

- Creating Files and Folders
- Creating Files
    1. Using the Explorer View:
        ◦ Open the Explorer view by clicking the Files icon in the Activity Bar or using the shortcut Ctrl + Shift + E.
        ◦ Right-click on the folder where you want to create a new file.
        ◦ Select New File, and then enter the file name.
    2. Using Keyboard Shortcuts:
        ◦ Open the Command Palette with Ctrl + Shift + P.
        ◦ Type File: New File and press Enter.
        ◦ A new untitled file will open in the editor.
    3. Directly in the Editor:
        ◦ Use the shortcut Ctrl + N (Windows/Linux) or Cmd + N (Mac) to create a new file.
        ◦ Save the new file with Ctrl + S (Windows/Linux) or Cmd + S (Mac), and specify the name and location.
- Creating Folders
    1. Using the Explorer View:
        ◦ Open the Explorer view with Ctrl + Shift + E.
        ◦ Right-click on the parent folder where you want to create a new folder.
        ◦ Select New Folder, and then enter the folder name.
- Opening Files and Folders
    1. Using the Explorer View:
        ◦ Navigate to the desired file or folder in the Explorer view and double-click to open it.
        ◦ You can also drag and drop files or folders into the editor window.
    2. Using the Command Palette:
        ◦ Open the Command Palette with Ctrl + Shift + P.
        ◦ Type Open File or Open Folder and select the appropriate option.
        ◦ Navigate to and select the file or folder you want to open.
    3. Using Keyboard Shortcuts:
        ◦ Open File: Ctrl + O (Windows/Linux) or Cmd + O (Mac).
        ◦ Open Folder: Ctrl + K, Ctrl + O (Windows/Linux) or Cmd + K, Cmd + O (Mac).
- Managing Files and Folders
    1. Renaming:
        ◦ Right-click on the file or folder in the Explorer view and select Rename.
        ◦ Alternatively, select the file or folder and press F2.
    2. Moving:
        ◦ Drag and drop the file or folder to the desired location within the Explorer view.
    3. Deleting:
        ◦ Right-click on the file or folder in the Explorer view and select Delete.
        ◦ Alternatively, select the file or folder and press Delete.
    4. Copying and Pasting:
        ◦ Right-click on the file or folder and select Copy or Cut.
        ◦ Right-click on the destination folder and select Paste.
- Navigating Between Files and Directories Efficiently
    1. Quick Open:
        ◦ Use Ctrl + P (Windows/Linux) or Cmd + P (Mac) to open the Quick Open dialog.
        ◦ Type part of the file name and select it from the list to open it.
    2. Go to Symbol:
        ◦ Use Ctrl + Shift + O to quickly navigate to symbols within the file.
        ◦ Type the symbol name and select it to jump to its location.
    3. File Explorer Shortcuts:
        ◦ Use Ctrl + Shift + E to focus the Explorer view.
        ◦ Use arrow keys to navigate through the file and folder structure.
        ◦ Press Enter to open the selected file or folder.
    4. Breadcrumb Navigation:
        ◦ Use the breadcrumb trail at the top of the editor to navigate to parent folders or sibling files.
        ◦ Click on any part of the breadcrumb to open a dropdown menu of the contents.
    5. Tabs and Split Editors:
        ◦ Open multiple files in tabs and switch between them by clicking on the tab or using Ctrl + Tab.
        ◦ Split the editor to view multiple files side by side by right-clicking on a tab and selecting Split Right or Split Down.
    6. Search:
        ◦ Use Ctrl + Shift + F to open the search view.
        ◦ Enter the search term to find text across all files in the workspace.
        ◦ Click on the search results to navigate to the specific location within the file.
    7. Recent Files:
        ◦ Use Ctrl + R to open a list of recently opened files.
        ◦ Select a file from the list to reopen it.


8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.

- In Visual Studio Code (VS Code), users can find and customize settings through the Settings interface. Settings can be adjusted at different scopes including user settings, workspace settings, and folder settings.
Accessing Settings
   1. Settings Interface:
        ◦ Keyboard Shortcut: Ctrl + , (Windows/Linux) or Cmd + , (Mac).
        ◦ Menu: Go to File -> Preferences -> Settings (Windows/Linux) or Code -> Preferences -> Settings (Mac).
   2. Command Palette:
        ◦ Open the Command Palette with Ctrl + Shift + P (Windows/Linux) or Cmd + Shift + P (Mac).
        ◦ Type Preferences: Open Settings and select it.
- Changing the Theme
    1. Using the Settings Interface:
        ◦ Open the Settings interface.
        ◦ Search for Color Theme in the search bar.
        ◦ Click on Color Theme under the Preferences section to see a list of available themes.
        ◦ Select the desired theme from the list.
    2. Using the Command Palette:
        ◦ Open the Command Palette (Ctrl + Shift + P or Cmd + Shift + P).
        ◦ Type Theme: Color Theme and select it.
        ◦ Choose a theme from the dropdown list.
- Changing the Font Size
    1. Using the Settings Interface:
        ◦ Open the Settings interface.
        ◦ Search for Font Size in the search bar.
        ◦ Locate the Editor: Font Size setting under the Text Editor section.
        ◦ Adjust the value to your desired font size (e.g., 14, 16).
- Customizing Keybindings
    1. Using the Keybindings Interface:
        ◦ Open the Command Palette (Ctrl + Shift + P or Cmd + Shift + P).
        ◦ Type Preferences: Open Keyboard Shortcuts and select it.
        ◦ The Keybindings interface will open, displaying all current keybindings.
        ◦ To change a keybinding, find the command you want to customize, click the pencil icon next to it, and press the new key combination.
        ◦ To remove a keybinding, click the key combination and then click the trash can icon.
    

9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?

- Steps to Set Up and Start Debugging a Simple Program
1. Install the Necessary Extensions
Before starting, ensure you have the appropriate language extension installed for the programming language you are using. For example:
    • Python: Python extension by Microsoft
    • JavaScript/TypeScript: JavaScript Debugger (bundled with VS Code)
    • C++: C++ extension by Microsoft
2. Open Your Project in VS Code
    • Launch VS Code.
    • Open your project folder by navigating to File -> Open Folder and selecting the folder containing your project files.
3. Create a Simple Program
Create a simple program file if you don't already have one. For example, create a file named app.py for Python 
4. Set Up the Debug Configuration
To debug your program, you need to create a debug configuration:
    1. Open the Debug view by clicking the Run icon in the Activity Bar on the side of the window or using the shortcut Ctrl + Shift + D.
    2. Click on the gear icon (or create a launch.json file) to open the debug configuration dropdown.
    3. Select the environment for your project (e.g. Python)
5. Set Breakpoints
To set a breakpoint, click in the left margin next to the line number where you want the execution to pause, or press F9 with the cursor on that line.
6. Start Debugging
    1. Go to the Debug view (Ctrl + Shift + D).
    2. Select the desired configuration from the dropdown menu at the top of the Debug panel.
    3. Click the green play button or press F5 to start debugging.

 - Key Debugging Features in VS Code
    1. Breakpoints: Set breakpoints to pause the execution of your code at specific lines. Conditional breakpoints and logpoints are also supported.
    2. Watch Expressions: Monitor variables or expressions' values during debugging.
    3. Call Stack: View the call stack to see the sequence of function calls that led to the current point in the execution.
    4. Variable Inspection: Inspect the values of variables at different points during the execution. Local, global, and environment variables can be examined.
    5. Step In, Step Out, Step Over: Navigate through your code line-by-line (F11 to step in, F10 to step over, Shift + F11 to step out).
    6. Debug Console: Execute commands and evaluate expressions in the context of the currently paused execution.
    7. Exception Handling: Configure VS Code to break execution on specific exceptions or all exceptions.
    8. Integrated Terminal: Run your program in an integrated terminal to see output and interact with it.
    9. Launch Configurations: Customize launch configurations in the launch.json file to specify how the debugger should start your application.
    10. Inline Values: View variable values directly in the editor next to the code, helping you understand the state of your application at a glance.


10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.


- Prerequisites
    1. Git Installation: Ensure Git is installed on your system. You can download and install it from git-scm.com.
    2. GitHub Account: Sign up for a GitHub account if you don't have one already.
- Setting Up Git in VS Code
    1. Open VS Code: Launch VS Code.
    2. Install Git Extension: The Git extension is built into VS Code by default. If you need additional features, you can install extensions like GitLens.
- Initializing a Git Repository
    1. Open Your Project: Open the folder containing your project files in VS Code.
    2. Initialize Repository:
        ◦ If your project folder is not already a Git repository, you will see an Initialize Repository button. Click on it.
        ◦ This will create a .git folder in your project directory, initializing a new Git repository.
    3. Making Commits
       1. Staging Changes:
        ◦ After making changes to your files, go to terminal and click on new terminal and ensure is on bash.
        ◦Then type git add . in the terminal and click enter.
       2. Committing Changes:
        ◦ After staging the changes, enter a commit message in the terminal by typing "git commit -m followed by "title of your work" and click enter.
    4. Pushing changes to github:
        ◦Type git push and click enter.


- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
-Reference point chat Gpt
- Submit your completed assignment by 1st July 

