
# 目錄
## [Step1 VScode Windows端開啟Py](#VScode_Windows)
## [Step2 VScode Raspberry 連線](#VScode_Raspberry)
## [Step3 開啟Raspberry 設定](#putty)
## [Step4 VNC 連線](#VNC_Link)



<a name="VScode_Windows"></a>
# Step1 VScode Windows端開啟Py

# 專案資料夾下CMD => Code . 
- 呼叫VsCode
- ![](./images/VScode_1.png) 

# 專案資料夾下CMD => Code . 
- 呼叫VsCode
- ![](./images/VScode_2.png) 

# 可以直接執行會在DOS環境顯示結果
- ![](./images/installRaspberryPi_3.PNG) 


<a name="VScode_Raspberry"></a>
# Step2 VScode Raspberry 連線

# 確定連接到
- ![](./images/RaspberryPi_Link1.PNG) 

# 電腦連線並確定 RobertRay IP
- ping RobertRay.local -4
- ![](./images/RaspberryPi_Link2.PNG) 


<a name="putty"></a>
# Step3 開啟Raspberry 設定

### 官網下載putty
- https://www.putty.org/

# 1.putty.exe 輸入IP
- ![](./images/putty_1.PNG)
- ![](./images/putty_2.PNG)

# 2.輸入帳號密碼
- ![](./images/putty_3.PNG)

# 3.Raspberry Pi SSH Link
https://alwaysai.co/docs/reference/raspberry_pi_setup.html
# sudo raspi-config
- ![](./images/putty_4.PNG)
- Interface Options 全部打開
- ![](./images/putty_5.PNG)
- ![](./images/putty_6.PNG)


<a name="VNC_Link"></a>
# Step4  VNC 連線
# 1.下載並安裝VNC-Viewer
- https://www.realvnc.com/en/connect/download/viewer/

# 2.VNC 使用 IP 登入
- ![](./images/VNC_1.PNG)


# 3.如果出現這個需接上顯示器調整螢幕
- ![](./images/VNC_2.PNG)
- ![](./images/VNC_3.PNG)


