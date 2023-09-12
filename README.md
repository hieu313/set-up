# Dùng Powershell để tải
## [Ngay khi cài lại win sẽ không có winget nên phải cài winget](https://learn.microsoft.com/en-us/windows/package-manager/winget/) 
### sao chép and paste trước khi cài mấy cái dưới:  
Add-AppxPackage -RegisterByFamilyName-MainPackage Microsoft.DesktopAppInstaller_8wekyb3d8bbwe

## IDM [Download](https://mirror2.internetdownloadmanager.com/idman641build18.exe?v=lt&filename=idman641build18.exe) : `có rất nhiều cái cần tải vui lòng cài sớm`
```diff
- lỗi không tải được hãy vào app_set_up
```
## Chrome
```diff
winget install --id=Google.Chrome  -e
```
## PHPStorm
```diff
winget install --id=JetBrains.PHPStorm -e  ;
```
## Visual Studio Code
```diff
winget install --id=Microsoft.VisualStudioCode -e  ;
```
## Notepad pp
```diff
winget install --id=Notepad++.Notepad++ -e  ;
```
## Xampp [phpversion: 8.2.4] [Download](https://sourceforge.net/projects/xampp/files/XAMPP%20Windows/8.2.4/xampp-windows-x64-8.2.4-0-VS16-installer.exe)
```diff
winget install --id=ApacheFriends.Xampp.8.2 -e  ;
```
## Git
```diff
winget install --id=Git.Git -e  ;
```
## WinRar
```diff
winget install --id=RARLab.WinRAR -e  ;
```
## CCleaner [Download](https://drive.google.com/u/0/uc?id=150ZQ_dxBigKyjsniYvUAwUI8jnrGJMvj&export=download) `|` [Trang chủ Crack](https://isangtao.com/download-ccleaner-professional-6-06-10144-huong-dan-cai-dat/)
```diff
+ Sau khi cài xong thì chạy quyền admin FILE CCleaner Professional Edition.cmd
- chỉnh cài đặt trước khi chạy
```
## Unikey [Download](https://www.unikey.org/assets/release/unikey43RC5-200929-win64.zip)
```diff
- lỗi không tải được hãy vào app_set_up
```
## TeamViewer [Download](https://download.teamviewer.com/download/TeamViewer_Setup_x64.exe)
```diff
+ điều khiển điện thoại trên máy tính thì cài app Host ở trên điện thoại
+ phần gán thì đăng nhập email và mật khẩu của teamviewer còn bí danh thì là tên hiện khi click vào avatar trong phần mềm
- lỗi không tải được hãy vào app_set_up
```
## Zalo [Download](https://zalo.me/download/zalo-pc?utm=90000)
```diff
winget install --id=VNGCorp.Zalo -e  ;
```
## Revo Pro (cần license) [Download](https://download.revouninstaller.com/download/RevoUninProSetup.exe)
```diff
winget install --id=RevoUninstaller.RevoUninstallerPro -e ;
```
## ShareX (print screen) [Download](https://github.com/ShareX/ShareX/releases/download/v15.0.0/ShareX-15.0.0-setup.exe)
```diff
winget install --id=ShareX.ShareX -e ;
```
## Everything [Download](https://www.voidtools.com/Everything-1.4.1.1024.x64-Setup.exe)
```diff
winget install --id=voidtools.Everything  -e
```
```diff
winget install --id=stnkl.EverythingToolbar  -e
```
## Right-click setup
```diff
winget install --id=Nilesoft.Shell  -e
```
## WinSCP (quản lý file trên web) [Download](https://winscp.net/eng/downloads.php)
```diff
winget install --id=WinSCP.WinSCP.RC  -e
```

## Cách set up Laravel :
### Có [Composer](https://getcomposer.org/Composer-Setup.exe):

### [Link How To Install Laravel](https://www.youtube.com/watch?v%253DsMXkSWFlV28%2526list%253DPL8y3hWbcppt2nWBglaxrQm_A5sRjstdnK)
### [Install Laravel](https://laravel.com/docs/10.x#your-first-laravel-project)
## Composer: (trong app_set_up)
- (check) __*composer -v*__ 

- __*composer diagnose*__
> If the status showing: **zip: extension not found, unzip not available, 7-Zip not available**  
> 1. Open Xampp Server, stop apache
> 2. find __php.ini__ file
> 3. find __*extension = zip*__
> 4. Remove the semi-colon and save the file
> 5. Restart apache server

- __*composer create-project laravel/laravel*__ <project_name>


## Office 2019 :
```diff 
+ Phải uninstall Microsoft Office... cũ trước rồi mới tải
```
- ### `Download`: https://officecdn.microsoft.com/pr/492350f6-3a01-4f97-b9c0-c7c6ddf67d60/media/en-us/ProPlus2019Retail.img  
- ### `Active Office 2019`: https://msguides.com/office-2019#Method_2_Using_batch_scripts
## [Foxit Editor pro](https://drive.google.com/u/0/uc?id=1ILn_ac5mIglkZXAWxSAkkUNC6oF_ER43&export=download)
## [Cốc Cốc](https://coccoc.com/download)
## [MSEdgeRedirect](https://github.com/rcmaehl/MSEdgeRedirect/releases/download/0.7.4.0/MSEdgeRedirect.exe) : Dùng để chuyển hướng win Search sang Chrome

## [Mysql Workbench](https://dev.mysql.com/downloads/workbench/) : Dùng để quản lý database
## [Google Drive Local Disk](https://dl.google.com/drive-file-stream/GoogleDriveSetup.exe) : up nhanh file lên Google Drive
## [TrafficMonitor](https://drive.google.com/file/d/1-c09eKFcZznImO1f8dimIZEOThwJ0zkO/view) (Đo tốc độ mạng)
## [Input Director](https://www.inputdirector.com/) : 1 chuột 1 bàn phím cho nhiều máy tính
## [Avast](https://www.avast.com/vi-vn/download-thank-you.php?product=FAV-ONLINE-HP&locale=vi-vn&direct=1)
## [Rainmeter](https://github.com/rainmeter/rainmeter/releases/download/v4.5.18.3727/Rainmeter-4.5.18.exe)
```diff
winget install --id=Rainmeter.Rainmeter -e  ;
```
## [Jaxcore](https://jaxcore.app/) (hơi lỗi)=> rainmeter

# Cách sử dụng:
- ## cài IDM full request
#### Download IDM crack [patch_active_IDM](https://github.com/hieu313/set_up_win/tree/master/linh_tinh)
1. win + s => Virus & threat protection => Virus & threat protection setting => manage settings => tắt realtime protection

2. copy patch.exe to 
```diff
C:\Program Files (x86)\Internet Download Manager
```
3. chuột phải file patch.exe and Run as administrator => crack button => finish button

4. delete patch.exe

- ## Steam -> wallpaper engine 

- ## Revo Pro:
1. Install and run once then close
   1.5 tắt wifi
2. Copy license "revouninstallerpro5.lic" to:
```diff
C:\ProgramData\VS Revo Group\Revo Uninstaller Pro
```

- ## Mysql Workbench:
1. connect mysql worlbench to xampp
https://stackoverflow.com/questions/57774867/using-xampp-and-mysql-workbench-together
2. export db to .sql file
https://stackoverflow.com/questions/22381577/mysql-workbench-how-to-export-mysql-database-to-sql-file


- ## Input Directory 
https://www.youtube.com/watch?v=fk5Fl2p6fnU
1. lấy ip máy phụ | vào SECURITY -> select from list -> click network -> ok
2. máy chính -> CLIENT SYSTEMS -> add button -> hostname : ip máy phụ
3. nhìn xuống dưới chỉnh sao cho thứ tự máy phù hợp

- ## file rainmeter :
1. tải rồi chạy các file .rmskin 
2. vào Document (thường nó sẽ tạo file ở đó) tìm folder Rainmeter rồi xóa đi 
3. ném file rainmeter trên git vào

- ## phpstorm plugin :
1. [Theme](https://plugins.jetbrains.com/plugin/12255-visual-studio-code-dark-plus-theme/versions#tabs)  
2. [Better Comment](https://plugins.jetbrains.com/plugin/10850-better-comments)

![Alt text](image.png)

- ## Add Git Bash vào terminal:
1. [Option để cài](https://stackoverflow.com/questions/56839307/adding-git-bash-to-the-new-windows-terminal)
2. [Hướng dẫn cài](https://fullstack.edu.vn/learning/windows-terminal-wsl?id=fe4bbf2f-f65c-496e-9aed-f42fecf0aca2) - `17:42`

- ## Cách thêm PHP storm vào NileSoft Shell:
1. Mở cmd với quyền Admin
```
setx PATH "%PATH%;C:\Program Files\Notepad++;C:\Program Files (x86)\JetBrains\PhpStorm 2023.1\bin"
```
* để kiểm tra đã set path chưa thì dùng lệnh:
```
echo %PATH:;=&echo.%
```
* nếu có rồi thì hãy nhập thử ___phpstorm64___ để xem có mở ứng dụng không
* ___Hãy làm điều tương tự với Notepad pp và các editors khác___   
2. Backup folder `Nilesoft Shell` trên git về và thay thế vào folder `C:\Program Files`
- ## Cách cài Ubuntu với WSL1:
1. Open PowerShell
```diff
wsl --install 
```
2. Windows Search:
```diff
Turn Windows features on or off
```
3. Bật `Windows Subsystem for Linux` rồi chờ restart lại
4. Xong vào MS Store tải `Ubuntu ... LTS` rồi open 
5. Nhập tài khoản mật khẩu mới
<a href="https://imgur.com/SyBm3al"><img src="https://i.imgur.com/SyBm3al.png" title="source: imgur.com" /></a>

