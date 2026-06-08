**Task2: The Invisible Manager**

An Operating System (OS) is the core software that coordinates everything happening on a computer. it sits between the user, applications, and the systems physical hardware acting as invisble manager

       User
 
       Applications

       Operating system

       Hardware


A real life analogy which will help you too understand the about this thing more 

Your hardware (CPU, RAM, storage, connected devices): The runways, airplanes, fuel systems, radar, and other physical infrastructure.

Your applications (web browser, game launcher): The various airlines and their passengers, all trying to take off, land, and request services.

Your operating system (Windows, Linux, macOS): The entire air traffic control system, directing all of this activity. It schedules resources, manages traffic, resolves conflicts, and ensures safety.

**System Privilege Layers**
1. *Kernel Space (Boss Area )*
   
Kernel OS ka sabse important aur powerful part hota hai.

Iske paas CPU, RAM, Hard Disk, Keyboard, Wi-Fi, Speakers sabka direct control hota hai.

Yeh hardware se directly baat kar sakta hai.

Is area mein sirf kernel aur trusted system components hi run karte hain.

Agar yahan koi error aa jaye, to poora system crash ho sakta hai.

Example:

Socho ek company hai. Kernel Space us company ka CEO office hai. Sirf authorized log hi andar ja sakte hain aur important decisions le sakte hain.

2. *User Space (Normal User Area )*

Yahan saare normal applications run karte hain:

Chrome, VS Code,Spotify,Games,WhatsApp Desktop

In applications ko hardware ko directly access karne ki permission nahi hoti.
Agar app ko koi kaam karna ho, jaise:


File open karni ho


Song play karna ho


Internet use karna ho

to woh kernel se request karta hai.
Example:

User Space company ke normal employees ki tarah hai. Employees directly CEO ke resources use nahi kar sakte. Unhe request bhejni padti hai.

**Operating System duties**

1) Process Management - Creates, schedules, prioritizes, and terminates running programs. The OS decides how much CPU time each process gets, making multitasking feel seamless

example: Opening multiple apps, like your browser, music player, and social media, without your computer freezing

2) Memory Management: Allocates RAM to processes, protects the app's memory from other processes, and reclaims memory when apps are closed. When RAM runs low, the OS uses virtual memory to keep your system stable

example: apps will get open and the OS will allocates the memory to particular one, and keeps each one of em islotaed from eachother

3) File System managment: Organizes file into directories and handle all the file paths and permissions and all work related to file 

example: like creating the new folder saving photo and all

4) User management: Handles multiple user accounts, authentication and permissions to determine who can access what and the only necessary information thats need to be watched 

example: logging into your snapchat or instagram account keeping your files inaccessible to other user accounts without password


5) Device Management: Load driver and provides a universal interface so apps can do there work properly 

example: pluggin in a new mouse, printer or any internal or external device



*Operating System Security*:

-Authentication: Verifies who you are through login passwords and biometrics

-Permissions: Controls exactly what each user and app is allowed to read, write, or execute

-Isolation: Keeps every process in its own protected box (kernel/user space separation)

-System Protection: Safeguards critical system files and settings from unauthorized changes



**Task 3: OS interaction and Landscape:**

*GUI (Graphical User Interface)*:

GUI woh interface hai jise hum roz use karte hain.

Isme humein icons, buttons, windows, menus, folders dikhte hain aur hum mouse ya touch se interact karte hain.

Examples: 
Windows Desktop, Android Phone Interface, MacOS, File Explorer

*CLI (Command-Line Interface)*:
CLI mein aap computer ko text commands likhkar instructions dete ho.
Yahan mouse clicks ki jagah commands type karni padti hain.

Examples: Windows Command Prompt (CMD), PowerShell, Linux Terminal, macOS Terminal

**Real World Operating Systems**

*Desktop*

Windows: The most widely used operating system on personal computers

Windows 10 (end-of-life), Windows 11

macOS: Apple's desktop OS, known for its polished GUI and integration with other Apple devices

Sonoma (14), Sequoia (15), Tahoe (26)

Linux: Not a single OS but a family of open-source operating systems called distributions

Ubuntu, Debian, Fedora

*Server*

Windows: Used in large networks, data centers, and corporate environments

Server 2016, 2019, 2022, 2025

Linux: The vast majority of web servers, trusted for its reliability and open-source nature

Ubuntu Server, Debian, CentOS, Red Hat

Unix: Large enterprises, finance, telecom, government

IBM AIX, Oracle Solaris

*Mobile*

Android: The most widely used mobile OS, which runs on phones, tablets, and smart devices

Android 14 - 16, Manufacturer versions

iOS: Apple's mobile OS running on iPhones, iPads, and other devices

iOS 17, 18, 26

*Embedded and IoT Devices*

Embedded Linux: Specialized OS built into devices with dedicated functions

OpenWrt, Ubuntu Core, Yocto Project

Real-Time OS: Designed for apps where tasks need guaranteed response times (aircraft controls)

FreeRTOS, VxWorks, QNX

*Virtual and Cloud*

Cloud/VM: Massive data centers that host websites, apps, and streaming services

Ubuntu LTS, Amazon Linux, Rocky Linux

Container-optimized: Lightweight alternatives to VMs that package just the app and its dependencies

Alpine Linux, Bottlerocket AWS, Flatcar Linux





