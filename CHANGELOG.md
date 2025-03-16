Changelog
===

<a target="_blank" href="https://apps.apple.com/app/rightmenu-master/6737160756" title="RightMenu Master for macOS">
  <img alt="RightMenu Master for macOS" src="https://jaywcjlove.github.io/sb/download/macos.svg" height="51">
</a>

## [v1.17.0](https://github.com/jaywcjlove/rightmenu-master/releases/tag/v1.17.0)

1. feat: add menu bar folder to display files.
2. feat: add show folder icon.
3. fix: fix menu bar authorization issue.
4. chore: check for receipt existence.
5. fix: resolve menu display internationalization issue.

---

1. feat: 添加菜单栏文件夹以显示文件。
2. feat: 添加显示文件夹图标。
3. fix: 修复菜单栏授权问题。
4. chore: 检查收据的存在。
5. fix: 修复菜单显示的国际化问题。

## [v1.16.0](https://github.com/jaywcjlove/rightmenu-master/releases/tag/v1.16.0)

1. feat: Add right-click menu for new file template settings
2. feat: Add option to quickly add common folders to right-click menu
3. feat: Add setting to open folder in Finder
4. fix: Show alert when folder does not exist
5. chore: Remove shortcut key settings

---

1. feat: 右键菜单新增新文件模板设置
2. feat: 右键菜单新增快捷添加常用文件夹选项
3. feat: 新增设置，可在 Finder 中打开文件夹
4. fix: 修复文件夹不存在时未弹出提示的问题
5. chore: 移除快捷键设置

## [v1.15.0](https://github.com/jaywcjlove/rightmenu-master/releases/tag/v1.15.0)

1. Feat: Add folder authorization prompt to the menu bar.
2. Feat: Support folder creation in folder selection.
3. Fix: Fix check for updates error.
4. Fix: Fix partial reauthorization issue after restart.
5. Fix: Update Finder activation method for macOS 14+ compatibility.
6. Fix: Fix menubar menu URL error.

---

1. 新增：在菜单栏添加文件夹授权提示。
2. 新增：在文件夹选择时支持创建文件夹。
3. 修复：修复检查更新时的错误。
4. 修复：修复部分重启后需要重新授权的问题。
5. 修复：更新 Finder 激活方式以兼容 macOS 14+。
6. 修复：解决菜单栏 URL 错误问题。

## [v1.14.0](https://github.com/jaywcjlove/rightmenu-master/releases/tag/v1.14.0)

1. feat: enhance error message for file sharing service.
2. feat: add Share File option to the menu bar.
3. fix: fix sync issue between cut shortcut and menu operation.
4. fix: fix the share popup selection box in the menu bar.

---

1. 新增：增强文件共享服务的错误提示。
2. 新增：在菜单栏添加“共享文件”选项。
3. 修复：解决剪切快捷键与菜单操作不同步的问题。
4. 修复：修复菜单栏中的共享弹窗选择框。

## [v1.13.0](https://github.com/jaywcjlove/rightmenu-master/releases/tag/v1.13.0)

1. feat: add separate settings for menu bar icon.
2. feat: add parent folder navigation in the menu bar.
3. feat: add version update check.
4. fix: fix UI freeze caused by popup dialog.

---

1. 功能：为菜单栏图标添加单独的设置。
2. 功能：在菜单栏中添加父文件夹导航。
3. 功能：添加版本更新检查。
4. 修复：修复弹出对话框导致的 UI 冻结问题。

## [v1.12.1](https://github.com/jaywcjlove/rightmenu-master/releases/tag/v1.12.1)

1. chore: remove FullDiskAccess permission settings.

---

1. 变更: 移除了 Full Disk Access（完全磁盘访问）权限设置。

## [v1.12.0](https://github.com/jaywcjlove/rightmenu-master/releases/tag/v1.12.0)

1. feat: Add "Open in Xcode" to menu bar folders.
2. fix: Fix folder icon issue.
3. feat: Add enable/disable Quick Look setting.
4. perf: Optimize Finder icon loading performance.

---

1. feat: 为菜单栏文件夹添加 "在 Xcode 中打开" 功能。
2. fix: 修复文件夹图标问题。
3. feat: 添加启用/禁用 Quick Look 设置功能。
4. perf: 优化 Finder 图标加载性能。

## [v1.11.0](https://github.com/jaywcjlove/rightmenu-master/releases/tag/v1.11.0)

1. feat: Add `copyTo` menu.
2. feat: Add `reset folder icon` menu.
3. feat: Add history tracking for target folders in move operations.
4. feat: Add `moveTo` menu.
5. feat: Add `create icns icon` menu.
6. feat: Add `convertTo` menu.
7. fix: Fix issue with selected files.
8. feat: Add shortcuts ⌘X/⌘V for cut and paste.

---

1. 功能: 添加 `复制到` 菜单。
2. 功能: 添加 `重置文件夹图标` 菜单。
3. 功能: 在移动操作中添加目标文件夹的历史记录。
4. 功能: 添加 `移动到` 菜单。
5. 功能: 添加 `创建 icns 图标` 菜单。
6. 功能: 添加 `转为格式` 菜单。
7. 修复: 修复已选文件的问题。
8. 功能: 添加快捷键 ⌘X/⌘V 用于剪切和粘贴。

## [v1.10.0](https://github.com/jaywcjlove/rightmenu-master/releases/tag/v1.10.0)

1. fix: fix issue with jumping to enable Finder extension on macOS 15.2
2. fix: fix issue with title not appearing on macOS 15.2
3. feat: add Cut and Paste menu
4. feat: add sendToDesktopSymlink menu
5. fix: resolve issue with default window opening position

---

1. 修复：修复 macOS 15.2 上跳转到启用 Finder 扩展的问题
2. 修复：修复 macOS 15.2 上标题不显示的问题
3. 新增：添加剪切和粘贴菜单
4. 新增：添加发送到桌面符号链接菜单

## v1.9.0

1. fix: Improved the authorization flow.  
2. feat: Added recognition for Xcode projects in the folder list.  
3. fix: Resolved the issue with the folder color setting menu display.  

---

1. 修复： 优化了授权流程。  
2. 功能： 在文件夹列表中新增对 Xcode 项目的识别功能。  
3. 修复： 修复了文件夹颜色设置菜单显示问题。  

## v1.8.0

1. 性能优化：缓存图标以提高性能。
2. 功能新增：添加文件夹图标颜色设置功能。
3. 功能新增：为显示常用应用程序添加状态栏菜单。

---

1. perf: Cache icons to improve performance.
2. feat: Add folder icon color setting feature.
3. feat: Add a status bar menu for showing common apps.

## v1.7.0

1. feat: Add "show total size" menu.  
2. feat: Add sorting options for the context menu.  
3. feat: Add detailed URL display to the Git remote menu.  
4. perf: Optimize icon loading to resolve performance issues.  
5. fix: Fix issue with loading volumes.  
6. fix: Fix display issue of mounted volumes in the context menu.  
7. chore: Optimize file size calculation logic.  
8. chore: Optimize Finder popup dialog message.  

---

1. 功能: 新增“显示总大小”菜单。  
2. 功能: 为右键菜单添加排序选项。  
3. 功能: 为 Git 远程菜单新增详细 URL 显示功能。  
4. 性能: 优化图标加载，解决性能问题。  
5. 修复: 修复加载卷的问题。  
6. 修复: 修复右键菜单中已挂载卷的显示问题。  
7. 其他: 优化文件大小计算逻辑。  
8. 其他: 优化 Finder 弹出对话框的消息显示。  

## v1.6.0

1. Feat: Add a menu bar option for common folder folding settings.  
2. Feat: Detect Git files and add an "Open Remote URL" menu option.  

---

1. 新增: 增加菜单栏中常用文件夹折叠设置的选项。  
2. 新增: 检测 Git 文件并添加“打开远程 URL”菜单选项。  

## v1.5.0

1. Feat: Add quick add to NewFile menu.  
2. Feat: Add quick add to common folders menu.  
3. Feat: Add more common folder settings.  
4. Feat: Add status bar folder submenus.  
5. Feat: Add error prompt for payment failures.  
6. Feat: Add menu to paste clipboard image into folder.  
7. Fix: Set the app language to follow the system by default.  
8. Fix: Fix issue with subfolders in common folders.  
9. Fix: Fix payment logic error.  
10. Perf: Optimize folder history menu.  
11. Refactor: Optimize reauthentication process.  

---

1. 新功能：在新建文件菜单中新增快速添加选项。  
2. 新功能：在常用文件夹菜单中新增快速添加选项。  
3. 新功能：新增更多常用文件夹设置。  
4. 新功能：在状态栏中新增文件夹子菜单。  
5. 新功能：为支付失败新增错误提示。  
6. 新功能：新增菜单以将剪贴板图片粘贴到文件夹中。
7. 修复：设置应用语言默认跟随系统。
8. 修复：修复常用文件夹中子文件夹的问题。  
9. 修复：修复支付逻辑错误。  
10. 性能优化：优化文件夹历史菜单。  
11. 重构：优化重新认证流程。  

## v1.4.0

1. Feat: Add quick add to NewFile menu.  
2. Feat: Add quick add to common folders menu.  
3. Feat: Add more common folder settings.  
4. Feat: Add status bar folder submenus.  
5. Feat: Add error prompt for payment failures.  
6. Feat: Add menu to paste clipboard image into folder.  
7. Fix: Set the app language to follow the system by default.  
8. Fix: Fix issue with subfolders in common folders.  
9. Fix: Fix payment logic error.  
10. Perf: Optimize folder history menu.  
11. Refactor: Optimize reauthentication process.  

---

1. 新功能：在新建文件菜单中新增快速添加选项。  
2. 新功能：在常用文件夹菜单中新增快速添加选项。  
3. 新功能：新增更多常用文件夹设置。  
4. 新功能：在状态栏中新增文件夹子菜单。  
5. 新功能：为支付失败新增错误提示。  
6. 新功能：新增菜单以将剪贴板图片粘贴到文件夹中。
7. 修复：设置应用语言默认跟随系统。
8. 修复：修复常用文件夹中子文件夹的问题。  
9. 修复：修复支付逻辑错误。  
10. 性能优化：优化文件夹历史菜单。  
11. 重构：优化重新认证流程。  

## v1.3.0

- feat: Improved performance by shrinking Finder icon size.  
- feat: Added folder history to the status bar menu.  
- feat: Supported reordering of frequently used folders.  
- feat: Enabled adding common apps through folder selection.  
- feat: Added common folders to the status bar menu.  

---

- feat: 通过缩小 Finder 图标尺寸提升性能。  
- feat: 在状态栏菜单中新增文件夹历史记录功能。  
- feat: 支持对常用文件夹进行重新排序。  
- feat: 支持通过选择文件夹添加常用应用程序。  
- feat: 在状态栏菜单中添加了常用文件夹功能。  

## v1.2.0

1. Fix: Fixed sidebar menu click issue on macOS 14.
2. Feat: Added folder history count setting.
3. Pref: Optimized icon import for better performance.
4. Perf: Improved right-click menu loading performance.
5. Feat: Added "Folder History" feature.
6. Fix: issue caused by Chinese file names

---

1. 修复：解决 macOS 14 上侧边栏菜单点击问题。
2. 新增：添加文件夹历史记录计数设置。
3. 优化：优化图标导入，提升性能。
4. 性能提升：改善右键菜单加载性能。
5. 新增：添加“文件夹历史记录”功能。
6. 修复：修复中文文件名称导致的错误

## v1.1.0

1. feat: Add a settings shortcut to the right-click menu.
2. feat: Add an import default common app feature.
3. feat: Add a common app feature.
4. feat: Add a `Collapse ContextMenu` feature.

---

1. 新功能: 在右键菜单中添加设置快捷方式。
2. 新功能: 添加导入默认常用应用的功能。
3. 新功能: 添加常用应用功能。
4. 新功能: 添加“折叠右键菜单”功能。