---
layout: post
title: Overview over Microsoft's developer tools for Windows 
category: general
---

If you just started programming on Windows this blog article might be interesting for you. I will give you an overview over the different tools Microsoft offers for developers. I will also give you some hints on how to get started with them. What this article won't cover are IDEs like Visual Studio or Visual Studio Code, as the article is more about helper tools.

*Source of the images used: Microsoft and Microsoft Learn*

## Dev Home

![Dev home Homepage](https://learn.microsoft.com/windows/images/devhome-welcome.png?wt.mc_id=studentamb_274787)

* [GitHub](https://github.com/microsoft/DevHome)
* [Documentation](https://learn.microsoft.com/windows/dev-home/?wt.mc_id=studentamb_274787)
* [Download](https://aka.ms/devhome)

To start I have to mention Dev Home. From here you can set up your development machine with the right tools, settings and repositories. You're also able to create a dashboard with different widgets that show you information about your development environment.

As Dev Home is relatively new it's still in preview, but still there are already two extensions available for it:

* [Dev Home GitHub Extensions](https://aka.ms/devhomegithubextension)
* [Dev Home Azure Extensions](https://aka.ms/devhomeazureextension)

## Microsoft PowerToys

![PowerToys settings screen](https://learn.microsoft.com/windows/images/pt-general.png?wt.mc_id=studentamb_274787)

* [GitHub](https://aka.ms/powertoys)
* [Documentation](https://learn.microsoft.com/windows/powertoys/?wt.mc_id=studentamb_274787)
* [Download](https://aka.ms/installpowertoys)

On every developers PC Microsoft PowerToys should not be absent. PowerToys is a collection of tools that help you to be more productive. The tools are open source and can be found on [GitHub](https://aka.ms/powertoys). Following an excerpt of my favorite tools (although all are great):

### Always on Top

![A window that is on top of another window](https://learn.microsoft.com/windows/images/pt-always-on-top.png?wt.mc_id=studentamb_274787)

Always on Top allows you to pin a window onto the foreground, before any other windows. So even when it looses focus it will stay on top of all other windows.

### Color Picker

![The color picker tool](https://learn.microsoft.com/windows/images/pt-color-picker.png?wt.mc_id=studentamb_274787)

Color Picker allows you to pick a color from your screen. It will show you the color code in many different formats, so you can easily use it in your code or your image editing software.

**Tip:** You can create your own custom formats that meet your needs.

### File Explorer Add-ons

![The file explorer add-ons showing a markdown preview in Windows Explorer](https://learn.microsoft.com/windows/images/pt-file-explorer.png?wt.mc_id=studentamb_274787)

File Explorer Add-ons add a bunch of Thumbnail providers and Preview handlers to Windows Explorer. This allows you to see a preview of your markdown files, SVGs, source code files and many more.

**Tip:** In the settings for File Explorer Add-ons under "Source code files" you can activate "Try to format the source for preview". This will format JSON and XML files automatically in the preview window.

### Keyboard Manager

![The keyboard manager tool settings](https://learn.microsoft.com/windows/images/pt-keyboard-manager.png?wt.mc_id=studentamb_274787)

Keyboard manager allows you to remap keys and shortcuts. From remapping Alt+R to Alt+Shift+R or even remapping to a sequence of characters like Ctrl+Alt+Shift+D to "Hello World" everything is possible.

**Tip:** I use this tool to remap Shift+F1 to F13, Shift+F2 to F14 and so on. This allows me to use the F13-F24 keys for shortcuts in my applications.

### PowerRename

![The PowerRename tool in action](https://learn.microsoft.com/windows/images/powerrename-demo.gif?wt.mc_id=studentamb_274787)

PowerRename allows you to rename multiple files at once. You can use regular expressions to find and replace text in the file names.

### PowerToys Run

![The PowerToys Run tool in action](https://learn.microsoft.com/windows/images/pt-powerrun-demo.gif?wt.mc_id=studentamb_274787)

PowerToys Run is a tool that allows you to quickly search for applications, files, folders and many more (Check out all the plugins in the settings). You can also use it to quickly run commands or do quick calculations.

### Quick Accent

![The Quick Accent tool in action](https://learn.microsoft.com/windows/images/pt-quick-accent.gif?wt.mc_id=studentamb_274787)

As the last item on this list I want to mention Quick Accent. Quick Accent allows you to quickly insert special characters into your text by simply holding the key for the character you want to insert. For example if you want to insert an "ä" you simply hold the "a" key and select the "ä" from the popup with the arrow keys.

**Tip:** If you hold shift plus a key you will get the uppercase version of the character.

## Windows subsystem for Linux

![The Windows subsystem for Linux opened in Windows Terminal](https://learn.microsoft.com/windows/wsl/media/run-any-distro-tarfile.png)

* [Documentation](https://learn.microsoft.com/windows/wsl/?wt.mc_id=studentamb_274787)
* [Installation guide](https://learn.microsoft.com/windows/wsl/installhttps://aka.ms/wslinstall?wt.mc_id=studentamb_274787)

Windows subsystem for Linux (WSL) allows you to use different linux distributions on your Windows PC.

This means you don't longer need quirks to run Linux applications on Windows.

Even GUI apps are supported.

![Different WSL GUI apps open](https://learn.microsoft.com/windows/wsl/media/wsl-gui-screenshot.png?wt.mc_id=studentamb_274787)

**Tip:** If WSL ever locks up you can force the termination of a distribution by running `wsl --terminate <distribution name>` in PowerShell or the command line.

### Windows subsystem for Android

Also worth mentioning if you're developing Android apps is the Windows subsystem for Android. It allows you to run Android apps directly on your Windows PC.

* [More information](https://learn.microsoft.com/windows/android/wsa/?wt.mc_id=studentamb_274787)

## WinGet

* [GitHub](https://github.com/microsoft/winget-cli)
* [Documentation](https://docs.microsoft.com/windows/package-manager?wt.mc_id=studentamb_274787)

WinGet is a package manager for Windows, which comes pre-installed with Windows 11. It allows you to install applications from the command line. It's similar to apt-get on Linux.

Just enter `winget install <package name>` to install a package.

**Tip:** You can also use WinGet to install and update applications from the Microsoft Store.

## Windows Terminal

* [GitHub](https://github.com/microsoft/terminal)
* [Documentation](https://docs.microsoft.com/windows/terminal/?wt.mc_id=studentamb_274787)
* [Download](https://aka.ms/terminal)

As already seen in the screenshots in the WSL section Windows Terminal is a great tool to work with the command line. It allows you to open multiple tabs and panes and organize them at your needs. You can also customize the look of the terminal as you please.

**Tip 1:** In the settings add a shortcut for quake mode. This allows you to open a dockable terminal window with a shortcut from anywhere.

**Tip 2:** Use [oh-my-posh](https://ohmyposh.dev/) to customize your terminal prompt and make working in your terminal even more fun.

## Closing words

Whether you're a beginner or an experienced developer,whether you use these tools or not, have fun developing on Windows! And make it your own! Please reach out to me on [X (Twitter)](https://x.com/theredcuber) or per [email](mailto:noraa.junker@outlook.com) and let me know what tools you're using. I hope this article was helpful and you were able to learn something new.
