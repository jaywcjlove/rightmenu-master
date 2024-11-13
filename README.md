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
    <a target="_blank" href="https://github.com/jaywcjlove/rightmenu-master/issues/new?assignees=&labels=support%2Cfeedback%2Cquestion&projects=&template=bug_report.yml&title=%F0%9F%99%8B%E2%80%8D%E2%99%82%EF%B8%8F+Support+%26+Feedback%3A+RightMenu+Master">Contact & Support</a>
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

### A Must-Have Application for Mac Users!

RightMenu Master is a highly configurable Finder extension that adds powerful functionality to the right-click menu and toolbar in Finder. It allows for quicker and more convenient operations such as moving and copying files, as well as creating new documents. The application also comes with several practical preset operations, further enhancing your work efficiency.

![RightMenu Master Screenshot 4](./assets/screenshots-4.png)

### Main Features

**■ Create New Files**

Finder lacks a convenient way to create new files in specific formats, but RightMenu Master makes it easy to do so with just one or two clicks. Additionally, you can upload custom templates to create new files in specific formats, improving efficiency.

![RightMenu Master Screenshot 3](./assets/screenshots-3.png)

**■ Quick Preview with Syntax Highlighting**

![RightMenu Master Screenshot 2](./assets/screenshots-2.png)

A quick preview extension is provided for viewing source text files with syntax highlighting. This extension handles supported file formats via [Uniform Type Identifiers (UTI)](https://developer.apple.com/library/archive/documentation/FileManagement/Conceptual/understanding_utis/understand_utis_intro/understand_utis_intro.html), rather than relying solely on file extensions. The UTI definitions include a list of associated file extensions and MIME types.

**■ Frequently Used Folders**

Supports custom frequently used folders for quick access to directories or to open a new terminal window directly in a specific folder.

**■ Common Apps**

Supports various editors and command-line tools (Terminal/iTerm) to quickly open the current directory, enhancing operational efficiency.

**■ Copy Features**

RightMenu Master offers various copy functionalities to make file operations more convenient. You can quickly copy the full file path, file name, or folder name, or even copy files/folders directly, significantly improving the flexibility and efficiency of file management.

**■ Copy File Path**

Quickly obtain the absolute path of a file for easy reference in other apps without needing to perform cumbersome manual operations.

**■ Copy Folder/File Name**

Supports copying folder names or file names to the clipboard for easy transfer and reference.

**■ Direct Delete**

With RightMenu Master, you can delete files or folders directly, saving time by skipping multiple steps in Finder, making the delete operation more efficient and convenient.

## Frequently Asked Questions

### Finder Extension Partial Menu Not Displaying Issue

When permissions are passively confirmed and then denied, reauthorizing permissions may cause the menu to not display. In this case, you need to restart the Finder extension. Restarting the computer can achieve this, but it’s cumbersome. Here are two simpler methods:

- Method 1: Execute `killall Finder` in the command line to restart Finder.  
- Method 2: Use the system’s `Force Quit Applications` feature to reload Finder. Open the `Force Quit Applications` window using the shortcut <kbd>⌘</kbd><kbd>⌥</kbd><kbd>esc</kbd>, find the `Finder` application, and click the `Relaunch` button below.

### Frequent Authorization Pop-Up Issues

In the application settings, go to `General` -> `Full Disk Access` -> Click to `Grant` to add the application to the `Full Disk Access` list.

### Enable Finder Extension

If you are prompted to enable the plugin, you need to run the following command in the terminal to enable the Finder extension.

```shell
pluginkit -e use -i com.wangchujiang.rightmenu-master.sync \
  && osascript -e 'quit app id "com.wangchujiang.rightmenu-master"' \
  && osascript -e 'tell application id "com.wangchujiang.rightmenu-master" to activate'
```

<!--idoc:config:
site: RightMenu Master
title: An exceptional Finder right-click menu enhancement tool that makes your right-click menu more powerful.
keywords: RightMenu, Finder, macOS, application, file management, create new file, copy functionality, enhancement tool
-->