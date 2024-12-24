<!--idoc:ignore:start-->
> [!TIP]
> Statement: This project is not open-source. This repository serves as the official website for collecting issues and user feedback. This approach is purely to save costs, as the app cannot pass the review without an official website.
<!--idoc:ignore:end-->

<div align="center">
  <br />
  <br />
  <a href="https://wangchujiang.com/rightmenu-master/">
  <img src="./assets/logo.png" alt="RightMenu Master LOGO" width="160" height="160">
  </a>
  <h1>RightMenu Master</h1>
  <!--rehype:style=border: 0;-->
  <p>
    <a href="./README.zh.md">中文</a> • 
		<a href="#frequently-asked-questions">FAQ</a> • 
    <a target="_blank" href="https://github.com/jaywcjlove/rightmenu-master/issues/new?assignees=&labels=support%2Cfeedback%2Cquestion&projects=&template=bug_report.yml&title=%F0%9F%99%8B%E2%80%8D%E2%99%82%EF%B8%8F+Support+%26+Feedback%3A+RightMenu+Master">Contact & Support</a> • 
    <a href="https://github.com/jaywcjlove/rightmenu-master/releases">Changelog</a>
  </p>
  <p>
    <a target="_blank" href="https://apps.apple.com/app/rightmenu-master/6737160756" title="RightMenu Master for macOS">
      <img alt="RightMenu Master for macOS" src="https://jaywcjlove.github.io/sb/download/macos.svg" height="51">
    </a>
  </p>
</div>

<div align="center">

minimum OS requirement: `macOS 14.0`

</div>

RightMenu Master — An exceptional Finder right-click menu enhancement tool that makes your right-click menu more powerful.

![RightMenu Master Screenshot 1](./assets/screenshots-1.png)

## A Must-Have Application for Mac Users!

RightMenu Master is a highly configurable Finder extension that adds powerful functionality to the right-click menu and toolbar in Finder. It allows for quicker and more convenient operations such as moving and copying files, as well as creating new documents. The application also comes with several practical preset operations, further enhancing your work efficiency.

![RightMenu Master Screenshot 4](./assets/screenshots-4.png)
![RightMenu Master Screenshot 3](./assets/screenshots-3.png)
![RightMenu Master Screenshot 2](./assets/screenshots-2.png)
![RightMenu Master Screenshot 6](./assets/screenshots-6.png)
![RightMenu Master Screenshot 5](./assets/screenshots-5.png)
![RightMenu Master Screenshot 7](./assets/screenshots-7.png)
![RightMenu Master Screenshot 8](./assets/screenshots-8.png)
![RightMenu Master Screenshot 9](./assets/screenshots-9.png)

## Main Features

- **Create New File:** Easily create new files in specific formats and upload custom templates.
- **Quick Preview with Syntax Highlighting:** Quickly preview code files with syntax highlighting.
- **File QR Code Sharing:** Quickly share files via QR codes and LAN download links.
- **Favorite Folders:** Customize favorite folders for quick access or to open a terminal window in a specific folder.
- **Folder Access History:** Record and quickly access previously visited folders.
- **Common Apps:** Quickly open your favorite editors or command-line tools (Terminal/iTerm).
- **Copy Features:** Provide various copy functions to simplify file path and name management.
- **Copy File Path:** Quickly copy the absolute path of a file.
- **Copy Folder/File Name:** Quickly copy the name of a folder or file.
- **Quick Paste:** Quickly paste images into Finder folders.
- **Direct Delete:** Quickly delete files or folders, simplifying the operation.
- **Identify and Add "Open Remote Git URL" Menu:** Automatically detect Git folders and add the "Open Remote URL" menu.
- **Show Total Size:** Show the total size and individual sizes of selected files or folders.
- **Set Folder Icon Color:** Quickly change or customize folder icon colors.
- **Cut and Paste Menu:** Add cut and paste functionality to enhance file management flexibility.
- **Create Shortcut on Desktop:** Create symbolic links (shortcuts) to files on the desktop.
- **Menu Bar Quick Navigation:** Quickly access favorite folder apps via the menu bar, improving operational efficiency.

## Frequently Asked Questions

### Finder Extension Partial Menu Not Displaying Issue

When permissions are passively confirmed and then denied, reauthorizing permissions may cause the menu to not display. In this case, you need to restart the Finder extension. Restarting the computer can achieve this, but it’s cumbersome. Here are two simpler methods:

- Method 1: Execute `killall Finder` in the command line to restart Finder.  
- Method 2: Use the system’s `Force Quit Applications` feature to reload Finder. Open the `Force Quit Applications` window using the shortcut <kbd>⌘</kbd><kbd>⌥</kbd><kbd>esc</kbd>, find the `Finder` application, and click the `Relaunch` button below.

### Frequent Authorization Pop-Up Issues

In the application settings, go to `General` -> `Full Disk Access` -> Click to `Grant` to add the application to the `Full Disk Access` list.

### Enable Finder Extension

If you are prompted to enable the plugin, you can run the following command in the terminal to enable the Finder extension. This issue is caused by a bug in macOS 15+ where the settings interface disappeared. It has been [fixed](https://forums.developer.apple.com/forums/thread/756711?answerId=812519022#812519022) in macOS 15.2.

```shell
pluginkit -e use -i com.wangchujiang.rightmenu-master.sync \
  && osascript -e 'quit app id "com.wangchujiang.rightmenu-master"' \
  && osascript -e 'tell application id "com.wangchujiang.rightmenu-master" to activate'
```

<!--idoc:config:
title: An exceptional Finder right-click menu enhancement tool that makes your right-click menu more powerful.
keywords: RightMenu, Finder, macOS, application, file management, create new file, copy functionality, enhancement tool
-->