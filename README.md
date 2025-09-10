# Install Autopsy and Analyze the Disk File and Folder Configuration

## AIM
To install **Autopsy** and use it to analyze the disk’s file and folder configuration for forensic investigation.

## REQUIREMENTS
- **Operating System**: Windows 10/11, macOS, or Linux
- **Tools**:  
  - [Autopsy Digital Forensics Platform](https://www.autopsy.com/)  
  - Optional: Sleuth Kit CLI tools for deeper analysis
- **Test Data**: Disk image file (`.dd`, `.img`, `.E01`)

## ARCHITECTURE DIAGRAM
```mermaid
flowchart TD
    A[Disk Image / Physical Drive] --> B[Install Autopsy]
    B --> C[Create New Case in Autopsy]
    C --> D[Add Data Source: Disk Image]
    D --> E["Autopsy Modules Run: File System, Metadata, Keywords"]
    E --> F[File & Folder Structure View]
    F --> G[Export / Recover Files]
```
## DESIGN STEPS:
### Step 1:
Download Autopsy from the official website and install it on your system.
<img width="1908" height="968" alt="image" src="https://github.com/user-attachments/assets/d9f86dc3-34e3-4e3d-80fd-6954eb24e335" />


### Step 2:
Launch Autopsy and create a new case.
<img width="604" height="410" alt="image" src="https://github.com/user-attachments/assets/5ae3a3ee-692d-4414-8e4b-05120d8a6e2b" />
<img width="990" height="589" alt="image" src="https://github.com/user-attachments/assets/ec87cd34-c6bf-4598-b0d3-418cd2d72d22" />



### Step 3:
Add your disk image or physical drive as the data source.

<img width="1083" height="679" alt="image" src="https://github.com/user-attachments/assets/e9b42e6d-b7a4-4455-b54d-cfc905d30349" />
<img width="1084" height="677" alt="image" src="https://github.com/user-attachments/assets/281b8445-f659-4b60-93fb-7dfb732db51c" />


### Step 4:
Allow Autopsy to run its built-in ingest modules (file system analysis, hash lookup, keyword search, metadata extraction).
<img width="1084" height="677" alt="image" src="https://github.com/user-attachments/assets/281b8445-f659-4b60-93fb-7dfb732db51c" />
### Step 5:
View the file and folder hierarchy in the left-hand tree panel.

### Step 6:
Export or recover files if required for the investigation.
<img width="456" height="269" alt="image" src="https://github.com/user-attachments/assets/cec7660b-2aac-4bbd-98e8-1d6b059e3766" />

## PROGRAM(Windows)

1. Download Autopsy from autopsy.com.
2. Install and launch the application.
3. Select **New Case → Name your case → Choose case folder**.
4. Click Add **Data Source → Select Disk Image → Browse to file**.
5. Choose ingest modules (file system, metadata, hash lookup, keyword search).
6. Wait for processing to finish.
7. Explore file/folder structure in the navigation pane.
8.Export selected files for further examination.

## OUTPUT:
File and Folder Configuration Analysis Results

## RESULT:
Autopsy was installed successfully and used to analyze disk, file, and folder configuration for forensic investigation.
