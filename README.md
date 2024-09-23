# Cannot change any options due to "server drafts location" error
![image](https://github.com/user-attachments/assets/7605b07f-abb6-450b-a94a-2fb143148923)

1. Right click on the start button, choose Run then type regedit to open the registry editor.
2. Browse to HKEY_CURRENT_USER\Software\Microsoft\Office\Common\Offline\Options
3. Right click and choose New > String and type Location as the name.
4. D_Click on Location, and add the path to your documents folder. (Example: C:\Users\Public\)
![image](https://github.com/user-attachments/assets/97e6285e-4e94-46a1-97f3-5ad1210bfeb1)


# Unlimited sharing folder in Win10

## 1. Step 1. Shared any folder first
ex: User\Publics
## 2. Step 2. Disable Maximum allowed
	2.1. R_Click ThisPC
	2.2. Click Manage
	2.3. Click Share Folder on the Left pane
	2.4. D_Click Shares (Left or Right pane)
	2.5. D_Click Publics folder icons on the right pane
	2.6. Click Disable Maximum allowed
	2.7. Click Allow this number of user: 90 or some thing elses
	2.8. Click OK to finish
![Unlimited sharing folder in Win10](https://github.com/thinhdoanvu/Office/blob/master/Hinh_Anh/unlimited%20sharing%20folder%20in%20Win10.PNG)
  
# Disable connect to another PC without Password require Or Cannot change Turn off password sharing in All Network configuration

## 1. Step 1. Remove Password for any Users
	1.1. R_Click ThisPC
	1.2. Click Manage
	1.3. Click Local Users and Groups on the Left pane
	1.4. D_Click Users (Left or Left pane)
	1.5. D_Click any User
	1.6. Change password by Enter key (remove password) 
![Remove Users password](https://github.com/thinhdoanvu/Office/blob/master/Hinh_Anh/Remove%20password.png)
## 2. Step 2. Turn password off in Network Sharing Center 
![Cannot change Turn password off sharing](https://github.com/thinhdoanvu/Office/blob/master/Hinh_Anh/Cannot%20change%20Turn%20off%20password%20sharing.PNG)

# Remote Desktop without Password requirement

## 1. Step 1. Allow remote Settings
	1.1. Open Control Panel
	1.1. Click System
	1.2. Click Remote Settings
	2.3. Remote Desktop Frame
	2.3. Click Allow connections to this computer
![Allow remote Settings](https://github.com/thinhdoanvu/Office/blob/master/Hinh_Anh/Allow%20Remote%20Settings.PNG)
# 2. Step 2. Remove password
	2.1. Click Control Panel 
	2.2. Click Administrative Tools
	2.3. Click Local Security Policy
# 3. Step 3. Group Policy Settings
	3.1. Click Security Settings 
	3.1. Click Local Policy
	3.2. Click Security Options
	3.3. Locate Accounts: Limit local account use of blank passwords to console logon only policy
	3.2. Click Disabled
![blank passwords for remote](https://github.com/thinhdoanvu/Office/blob/master/Hinh_Anh/Disabled%20Password%20Remote%20Desktop.PNG)

# Adding Windows Boot after Install Ubuntu OR Losing Windows Boot
## 1. sudo os-prober
## 2. sudo update-grub
## 3. sudo apt-get update
![Adding Windows Boot in Ubuntu](https://github.com/thinhdoanvu/Office/blob/master/Hinh_Anh/add_Windowsboot_inUbuntu.png)
