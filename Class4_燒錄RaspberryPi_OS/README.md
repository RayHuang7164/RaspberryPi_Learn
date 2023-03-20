
# 目錄
## [Step1 安裝Raspberry Pi OS](#Install_RaspberryPiOS)
## [Step2 Raspberry 連線](#Raspberry_Link)
## [Step3 開啟Raspberry 設定](#putty)
## [Step4 VNC 連線](#VNC_Link)



<a name="Install_RaspberryPiOS"></a>
# Step1 安裝Raspberry Pi OS

### 官網下載Raspberry Pi OS 
- https://www.raspberrypi.com/software/
- ![](./images/installRaspberryPi_1.PNG)

# 安裝RaspberryPiOS_imager_1.7.4.exe
- ![](./images/installRaspberryPi_2.PNG) 

# Install_Raspberry Pi OS
- ![](./images/installRaspberryPi_3.PNG) 

# Install_Raspberry Pi OS 設定
- 建立名稱、開啟SSH
- ![](./images/installRaspberryPi_4.PNG) 

# 建立使用者帳號、密碼、WiFi (才能直接連線)
- ![](./images/installRaspberryPi_5.PNG) 
- ![](./images/installRaspberryPi_6.PNG)
- ![](./images/installRaspberryPi_7.PNG)



<a name="Raspberry_Link"></a>
# Step2 Raspberry 連線

### 確定RaspberryPi 開機、連線
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
- 修改設定檔 (重啟)
- sudo nano /boot/config.txt
- ![](./images/VNC_4.PNG)


