# Windows Longhorn 4074 build Multilingual User Interface Pack
### 为您的 Windws Longhorn build 4074 添加简体中文、繁体中文及更多语言！

编译方法：
1. 从 https://winbetauser.github.io/files/lh4074mui-src-latest-release.zip （仅正式版）或 Release 处下载源代码（不建议下载测试版，因为它可能不稳定）。  
2. 从 https://files.jrsoftware.org/is/5/innosetup-5.6.1-unicode.exe 下载 Inno Setup 5.6.1 Unicode 安装包，并安装它（5.5.6 - 5.6.0 和非 Unicode 版本也行，但不建议）。记得勾选安装 Inno Setup Preprocessor！  
3. 打开 installer.iss 文件，去除 SignTool=winbetamui 和 SignedUninstaller=yes 这两行，然后编译 installer.iss 文件，编译完成的文件在源代码根目录下的 compiled_installer 文件夹。  

#### 反馈
产品交流群: https://teams.live.com/l/invite/FEAiNqXRjDpEszT-gQ  

邮箱: 
 WinBetaUser (团队队长): markta111@outlook.com  
 Nicrozoft: haha666_666@outlook.com 、[备用]haha666_1@outlook.com  
 AndyChung123: chunghuenpang@hotmail.com  

感谢支持！
