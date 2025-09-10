# EXP 3 : INSTALL AUTOPSY AND ANALYSIS THE DISK, FILE AND FOLDER CONFIGURATION

## AIM:
To install Autopsy software on windows operating system and analyse the file and folder configuration.

## EQUIPMENT REQUIRED:
● Hardware: Personal Computer (PC)
```
Register Number:212223100022
Name: KISHAN SHREE B
```
## DESIGN STEPS:
### Step 1:
Install Autopsy using the terminal with the command:

### Step 2:
Launch Autopsy from the terminal or application menu and create a new case.

### Step 3:
Add a disk image or file to the case and analyze the contents such as deleted files, metadata, and folder structure.

## INSTALLATION PROCEDURE:
### Step1:Download Autopsy
• Visit Autopsy Official Website and download the latest version.

• Double-click the downloaded file and follow the on-screen instructions.
![Screenshot 2025-04-25 085320](https://github.com/user-attachments/assets/bae6c8c1-2d94-4639-84aa-cac512925854)


## **Implementation steps:**

### **1. Copy Files to the Virtual Disk**  
- Open **File Explorer** → Go to the new drive (`D:`), where the folder created in the New Virtual Disk
- Create a new folder or use the entire disk and then copy **images or files** into it.  

### **2. Delete the Files**  
- Select any one or two images → Press **Delete**.  
- Empty the **Recycle Bin** to permanently delete them.  

### **3. Recover Deleted Files Using Autopsy**  
### **Open Autopsy & Create a New Case** 

- Launch **Autopsy** and **Run as a administrator**  
- Click **Create New Case**.  
![Screenshot 2025-04-22 214658](https://github.com/user-attachments/assets/89ed73c4-ca95-4f21-b2f1-3a5ba2b67781)


- Enter a **Case Name** (e.g., `Autopsy-1`).  
- Choose a **Case Folder** location.  
- Click **Next** → Click **Finish**.  


![Screenshot 2025-04-22 215824](https://github.com/user-attachments/assets/6d60e194-4850-421e-9bf9-b2c758f49d81)

### **Add the Virtual Disk as an Evidence Source**  
- Click **Add Data Source**  → **Select Host**
![Screenshot 2025-04-22 220051](https://github.com/user-attachments/assets/749bc8d2-22f8-464f-9824-ca774c859132)


- Select **Local Disk** → **next** 

![Screenshot 2025-04-22 220110](https://github.com/user-attachments/assets/e56a9fe1-1c83-4256-aea6-16004f93e63e)



- Select Disk → **Choose the VHD drive (`New Volume(E:`)**



- Click **Next** → Keep default settings → Click **Finish**.  
- Wait for Autopsy to process the disk.  

### **Recover Deleted Files**  
- Go to **File Views** (left panel).  


- Click **Deleted Files** → Find your deleted images.  
- Right-click an image → Click **Extract File**.  

<img width="1622" height="656" alt="image" src="https://github.com/user-attachments/assets/1257351a-3b82-44a5-9d52-1e3dd2e6473a" />


- Click OS Account

![Screenshot 2025-04-25 090001](https://github.com/user-attachments/assets/809a4b18-877a-4b69-b2dd-d30c5e3151fe)


## Result:
Successfully extracted the deleted files from unallocated space using the Autospy tool.
