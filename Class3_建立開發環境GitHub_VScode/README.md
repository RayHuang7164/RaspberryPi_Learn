
# 目錄
## [Step1 安裝Python](#Install_Python)
## [Step2 安裝Git](#Install_Git)
## [Step3 安裝VSCode](#Install_VSCode)
## [Step4 連結GitHub](#Link_GitHub)
## [Step5 專案內快速開啟VSCode](#Open_Vscode)
## [Step6 ssh Record 清除](#ssh_Record)


<a name="Install_Python"></a>
# Step1 安裝Python

### 官網下載Python   
- https://www.python.org/
- 有舊版本的要先使用安裝檔進行完全移除Uninstall
- 原本的安裝資料夾也需全部移除

# 版本選擇(選擇通用且穩定的版本)

- Colab
- https://colab.research.google.com/

![](./images/Colab_python_version.PNG)
- Python 3.9.16 =>但是此板沒有Windows

#
# 選穩定的(使用系統管理員身分執行安裝)
- https://www.python.org/downloads/windows/

- ![](./images/Python3810.PNG) 

# Install_Python Customize Path
- ![](./images/Install_Python_1.png) 

# Install_Python Setup Path
- ![](./images/Install_Python_2.png) 

# Install_Python Path Length Limit
- ![](./images/Install_Python_3.png) 

# Install_Python 環境確認
- ![](./images/Install_Python_4.png) 

<a name="Install_Git"></a>
# Step2 安裝Git

### 官網下載Git
- https://git-scm.com/

# 版本選擇
- ![](./images/Install_Git_1.png) 

# Install_Git 重要設定
- ![](./images/Install_Git_2.png) 

# Install_Git 環境確認
- ![](./images/Install_Git_3.png) 

<a name="Install_VSCode"></a>
# Step3 安裝VSCode

### 官網下載VSCode
- https://code.visualstudio.com/

# VSCode 1 登入畫面
- ![](./images/VSCODE_1.png)

# VSCode 2 延伸模組=>中文化
- ![](./images/VSCODE_2.png)
- 重新啟動後
- ![](./images/VSCODE_3.png)

# VSCode 3 設定自動儲存
- ![](./images/VSCODE_4.png)
- ![](./images/VSCODE_5.png)


# VSCode 4 延伸模組=>安裝Python輔助工具
- ![](./images/VSCODE_6.png)

# VSCode 5 建立專案資料夾
- ![](./images/VSCODE_7.png)
- ![](./images/VSCODE_8.png)

# VSCode 6 建立ipynb (JupyterNotebook)
- ![](./images/VSCODE_9_ipynb_JupyterNotebook.png)
# 選擇JupyterNotebook使用Python版本
- ![](./images/VSCODE_10_ipynb_Python_FW.png)
# 接受JupyterNotebook安裝相關套件
- ![](./images/VSCODE_11_ipynb_Python_Other.png)

# VSCode 7 建立py檔案
- ![](./images/VSCODE_12_Build_py.png)

# 選擇Python運行版本
- ![](./images/VSCODE_12_py_FW.png)

# Check Function link
- ![](./images/VSCODE_13_Check_Function_link.png)

# 打開終端機
- ![](./images/VSCODE_14_Open_terminal.png)

# 修改預設終端機
- ![](./images/VSCODE_15_defaul_terminalt.png)

# Windows Python 預設啟用程式 
- (錯誤時會卡住 Ctrl+C 跳出)
- ![](./images/VSCODE_16_Windows_defaul_PythonApp.png)
- ![](./images/VSCODE_17_Windows_defaul_PythonAppFix.png)

<a name="Link_GitHub"></a>
# Step4  連結GitHub
# 1.先申請並驗證通過個人GitHub帳號
- https://github.com/

# 2.下載並安裝GitHub CLI (指令在Manual內)
- https://cli.github.com/

# 3.VSCode重啟新增Git Bash
- ![](./images/GitHub_1_OpenGitBash.png)


# 4.建立Git在專案內並設定相關資料
- https://git-scm.com/book/zh-tw/v2/%E9%96%8B%E5%A7%8B-%E5%88%9D%E6%AC%A1%E8%A8%AD%E5%AE%9A-Git

# 專案資料夾建立git進行專案管理
- git init 
- ls -al 確定.git隱藏檔有出現
# 設定識別資料
'''
$ git config --global user.name "John Doe"

$ git config --global user.email johndoe@example.com
'''
-![](./images/GitHub_3_Bulid_git.png)

# 5.GitHub_Link
- gh auth login 
- https://cli.github.com/manual/
- ![](./images/GitHub_4_GitHub_Link.png)
- ![](./images/GitHub_5_Authorize_github.png)
- ![](./images/GitHub_6_logged_Finish.png)

# 6.建立資料夾在GitHub端
- gh repo 專案資料夾名稱 --public --source=. --remote=upstream
- ![](./images/GitHub_7_CreateFolderCloud.png)

# 7.同步資料在GitHub端
- ![](./images/GitHub_8_sync_All_Data.png)


# Step5 專案內快速開啟VSCode
<a name="Open_Vscode"></a>
- ![](./images/Quick_VsCode.png)



# Step6 ssh Record 清除
- 連不上時刪除所有記錄
- 此文件內所有東西刪掉
<a name="ssh_Record"></a>
- ![](./images/SSH_Record.PNG)
