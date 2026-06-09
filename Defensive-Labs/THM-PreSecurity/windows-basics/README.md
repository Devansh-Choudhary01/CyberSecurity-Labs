**Task 2: Exploring the Windows workspace**

Earlier microsoft was much simpler and easier to use, Early computers ran on MS-DOS which usually used to show black screen where we had to type the commands instead of clicking icons.
In 1985, Microsoft released windows 1.0 a basic graphical user interface (GUI) built on top of DOS, introducing windows,menus and mouse controls to personal computers. 

*Logging in and authentication*

The authentication process verifies your identity and determines the actions you're allowed to take once logged in. When a Windows system starts, it displays a login screen where a user account must be selected and authenticated with a password, PIN, or another verification method

• Guest: A restricted account intended for temporary access, with minimal permissions and no ability to change system settings

• Standard: A user account for everyday tasks, such as running applications and changing personal settings, without access to system-wide changes

• Administrator: A privileged account with full control over the system, including software installation, configuration changes, and user management


*The windows Desktop*

1. Desktop icons: Shortcuts to items like the Recycle Bin, folders, and frequently used applications. It is fully customizable
2. Start menu: Primary way to access applications, settings, and power options. From here, you can log out, restart, or power off your machine
3. Search: Quickly find applications, files, folders, and system settings by using keywords
4. Task View: Allows you to see all currently open windows and quickly switch between them
5. Pinned Applications and Folders: Your most used applications and folders can be pinned here
6. Network and Audio settings: This section can be customized to suit your needs
7. Date and Time: Opens up to a full calendar. Date and time settings can be accessed here, too
8. Notifications: Displays computer or application notifications. Network and other settings can also be accessed

**Task 3: Configuring and securing windows**

Updating your OS or apps is like changing flights or reserving a seat. Installing a new app is comparable to scheduling a new flight, and removing apps is like canceling a booking you no longer need. These three processes enable you to make the necessary changes to your system

*The Task Manager*

Task Manager is a built-in Windows tool that allows you to monitor what is happening on your system in real time. It allows you to view running applications and background processes, as well as check system performance, including CPU and memory usage

Task Manager has five tabs to help you keep track of your system.
1. Processes: Currently running apps and background processes, and their resource usage
2. Performance: Graphs and statistics for system resources such as CPU, memory, and network
3. Users: Currently logged-in users and used resources 
4. Details: A more technical view of running processes, including process IDs (PIDs)
5. Services: Windows services and their current status (running or stopped)

**User Management & Access Control**

Windows enforces security boundaries through granular account management and permission structures:

**1. Account Types**

* **Administrator Account:** Holds absolute privileges over the entire system. Can modify system files, install hardware drivers, and alter global security policies.

* **Standard User Account:** Restricted account type. Can run pre-installed applications and change personal settings, but cannot execute tasks that impact system-wide security without elevation.


**2. User Account Control (UAC)**

**UAC** is a fundamental security architecture boundary in Windows. It ensures that apps run strictly in a non-privileged context unless an Administrator explicitly authorizes elevated privileges. It prevents malware from silently executing with full system access.

---

**Essential Windows Command Line (CLI) Reference**

A professional analyst must be comfortable navigating via the Command Prompt (`cmd.exe`) and PowerShell.

| Command | Purpose | Security Context |
| :--- | :--- | :--- |
| `whoami` | Displays the current logged-in user and privilege level. | Used during initial access to check execution context. |
| `hostname` | Prints the network name of the local computer asset. | Asset identification during incident triage. |
| `net user` | Lists all local user accounts registered on the system. | Auditing for rogue accounts or backdoor access. |
| `net localgroup administrators` | Lists all users with local administrator privileges. | Identifying over-privileged user states. |
| `ipconfig /all` | Displays comprehensive network adapter configurations and DNS details. | Finding target subnet boundaries and gateway details. |
| `systeminfo` | Pulls detailed OS configuration, hotfixes, and patch levels. | Essential for detecting missing patches / Privilege Escalation. |





