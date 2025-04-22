# EXP1: INSTALL VMWARE, INSTALL KALI LINUX AND INSTALL SLEUTH KIT. 
## AIM:

To install VMware, set up Kali Linux as a virtual machine, and install Sleuth Kit for digital forensic analysis.

```
Register Number: 212222040128
Name: RAGHUL S
```

## EQUIPMENT REQUIRED:
  ●	Hardware: Personal Computer (PC)


## DESIGN STEPS:

### Step 1:

Install VMware Workstation Player on your system and download the Kali Linux ISO from its official website.

### Step 2:

Create a new virtual machine in VMware using the Kali Linux ISO, configure the hardware settings, and complete the installation of Kali Linux.

### Step 3:

Open the terminal in Kali Linux and run the command sudo apt install sleuthkit to install Sleuth Kit.

## INSTALLATION PROCEDURE:
INSTALLING VMWARE:
### Step 1. Download VirtualBox
  •	Go to: https://www.virtualbox.org/
  
  •	Click on the “Downloads” link in the left menu
  
  •	Under VirtualBox x.x.x platform packages, click Windows hosts
![image](https://github.com/user-attachments/assets/28b2e57a-d806-4e06-b4d5-5a8b69f7e729)


### Step 2. Run the Installer
  •	Locate the downloaded .exe file (usually in your Downloads folder)
![image](https://github.com/user-attachments/assets/7cbbd633-a8c2-4e4a-bd70-cdceca7f7533)

  
  •	Double-click it to run the installer
### Step 3. Installer Wizard
![image](https://github.com/user-attachments/assets/4e1322e6-bcd8-4439-96e1-035595e5847d)


  •	Click Next
  
  •	Keep default settings unless you want to change install location or features
  
  •	Click Next
### Step  4. Network Interface Warning
  •	Click Yes to proceed (this may temporarily disconnect your internet)
  ![image](https://github.com/user-attachments/assets/fc27e8c9-87f3-47be-a144-3e07124d6c9a)

### Step  5. Begin Installation
  •	Click Install
  ![image](https://github.com/user-attachments/assets/6241549f-0079-4fba-9b9a-09f76bca4db6)
  
  •	If asked for permission by User Account Control (UAC), click Yes

## OUTPUT:
  •	Click Finish
  
  •	VirtualBox will launch (if the checkbox is ticked)
  ![image](https://github.com/user-attachments/assets/dff98782-4186-4717-b97f-e59adc929945)

## INSTALLING KALI LINUX:
### Step 1: Open Oracle VirtualBox
  •	After installing VirtualBox, open it.
  
  •	The main screen of VirtualBox should appear.
### Step 2: Download Kali Linux VirtualBox Image
  •	Go to:
   https://cdimage.kali.org/kali-2024.4/kali-linux-2024.4-virtualbox-amd64.7z
   
  •	Download the .7z file (Kali Linux VirtualBox image)
 ![image](https://github.com/user-attachments/assets/836dfb78-91bf-42b7-aec8-bef23f9e23b8)

  
### Step 3: Extract the File
  •	Use 7-Zip or WinRAR to extract the .7z file:
  
  o	Right-click on the downloaded file
  
  o	Select "Extract Here" or "Extract to Folder"
  
  •	You’ll get a folder containing a .vbox file (VirtualBox Machine Definition File)
### Step 4: Import Kali Linux into VirtualBox
  •	Open VirtualBox
  
  •	Click on File → Import Appliance
  ![image](https://github.com/user-attachments/assets/da7fd3b1-a9b0-40fb-93dc-f0d9a1b15bfa)
  
  •	Click Choose, then browse to the extracted .vbox file
  
  •	Select the .vbox file and click Next
  
  •	Keep the default settings as they are
  
  •	Click Import  Wait for the import process to complete
### Step 5: Start Kali Linux
  •	Once imported, you will see "Kali Linux" in the left panel
  
  •	Select it and click Start and the Kali Linux will boot up
  ![image](https://github.com/user-attachments/assets/07334803-be51-4b19-954f-b33010c68fa6)
  ![image](https://github.com/user-attachments/assets/68e7a706-ce1d-4ad1-8ebf-c313de6fcf92)
e![VirtualBox_kali-linux-2024 4-virtualbox-amd64_22_04_2025_12_35_05](https://github.com/user-attachments/assets/f895b594-8cee-495d-8851-50636f7f5f39)

  
## OUTPUT:
  •	After login (default username: kali, password: kali)
  
  •	Open the Terminal (black monitor icon)
  
  •	Try the basic Linux commands:
 ![image](https://github.com/user-attachments/assets/12e9ffe2-81b4-487b-8899-e9ede315fdaa)

  
## INSTALLING SLEUTH KIT:
  •	Download Sleuth Kit from www.sleuthkit.org/sleuthkit/download.php
  ![image](https://github.com/user-attachments/assets/9355a68d-e06d-4642-971b-8cda41f6229e)
  
  ●	Move the downloaded folder to the program files.
  
  ●	Go to the system environment variables.
  ![image](https://github.com/user-attachments/assets/389dfdaf-7b24-458e-949c-ec48b2209ae3)

  ![image](https://github.com/user-attachments/assets/9b23a2db-287e-45e0-8037-5abdadccc401)
  
  ● Click environment variables.

![image](https://github.com/user-attachments/assets/e8eaa863-a273-4dd4-a6bc-4703688d10a1)

  
  ●	Click the path
  
  ●	Now add the sleuth kit folder address.
  
  ●	And the click ok. USING OF SLEUTH KIT:
  ![image](https://github.com/user-attachments/assets/c8ec3ab7-646e-4f93-a02a-54a2698f05fa)
  
## OUTPUT:
  ● Open command prompt and type fls -V to check sleuth kit is installed or not.
  
  ●	Lists partition layout
  ![image](https://github.com/user-attachments/assets/13fd54bd-3807-48b9-a923-25e85f1a9735)
  
  ●	Lists files and directories
  ![image](https://github.com/user-attachments/assets/968d265d-8065-47a3-9e38-2f4032bb2535)

These are the some of the commands used in the Sleuth kit.

## RESULT:
Thus the vmware, kali linux and sleuth kit has been installed successfully.

