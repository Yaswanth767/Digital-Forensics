# Experiment-1: Evidence Acquisition Using FTK Imager

**Course / Lab:** Digital Forensics Lab  
**Experiment No.:** 1  
**Title:** Evidence Acquisition Using FTK Imager  


---

## Aim
To capture RAM data and create a forensic disk image using FTK Imager.

---

## Requirements
- FTK Imager  
- Windows operating system  

---

## Description
- FTK Imager is a forensic acquisition tool used to create exact copies (disk images) of storage devices.  
- It allows capturing RAM data, entire drives, or specific partitions without altering original evidence.  
- Investigators use it to preview, preserve, and export data for further forensic analysis.  

---

## Part A — Acquiring Volatile Memory (RAM) Using FTK Imager

**Step-1:** Right click on the FTK Imager tool and select **Run as administrator**.  
![Step 1](https://github.com/Yaswanth767/Digital-Forensics/blob/41c17321ad918d91408dfba92a1c1df5c7002e8a/images/ex1.1.jpg)

**Step-2:** On the top menu bar, click **File** and select **Capture Memory** from the drop-down list.  
![Step 2](https://github.com/Yaswanth767/Digital-Forensics/blob/41c17321ad918d91408dfba92a1c1df5c7002e8a/images/ex1.2.jpg)

**Step-3:** A dialog box will appear. Select the destination path to your file and provide the file name with `.mem` extension. (Pagefile and AD1 file options are optional.)  
![Step 3](https://github.com/Yaswanth767/Digital-Forensics/blob/41c17321ad918d91408dfba92a1c1df5c7002e8a/images/ex1.3.jpg)

**Step-4:** Click the **Capture Memory** button to start acquisition of memory.  
![Step 4](https://github.com/Yaswanth767/Digital-Forensics/blob/41c17321ad918d91408dfba92a1c1df5c7002e8a/images/ex1.4.jpg)

**Step-5:** A progress bar in green colour will indicate the capture status. The time taken to capture RAM depends on the system’s RAM size. After completion, the captured memory file will be available in the chosen destination folder.  
![Step 5](https://github.com/Yaswanth767/Digital-Forensics/blob/41c17321ad918d91408dfba92a1c1df5c7002e8a/images/ex1.5.jpg)

---

## Part B — Acquiring Non-Volatile Memory (Disk Image) Using FTK Imager

**Step-1:** On the top right menu bar, click **File** and select **Create Disk Image** from the drop-down menu.  
![Step 1](https://github.com/Yaswanth767/Digital-Forensics/blob/41c17321ad918d91408dfba92a1c1df5c7002e8a/images/ex1.6.jpg)

**Step-2:** In the dialog box, choose the source evidence type like **Physical Drive, Logical Drive, Image File, or Contents of a folder**.  
![Step 2](https://github.com/Yaswanth767/Digital-Forensics/blob/41c17321ad918d91408dfba92a1c1df5c7002e8a/images/ex1.7.jpg)

**Step-3:** Fill in the case information (Case Number, Evidence Number, Examiner Name, Unique Description, Notes) and click **Next**.  
![Step 6](https://github.com/Yaswanth767/Digital-Forensics/blob/41c17321ad918d91408dfba92a1c1df5c7002e8a/images/ex1.8.jpg)

**Step-4:** Choose the destination folder and give a file name for the image.  
![Step 7](https://github.com/Yaswanth767/Digital-Forensics/blob/41c17321ad918d91408dfba92a1c1df5c7002e8a/images/ex1.9.jpg)


FTK Imager will display progress along with hash values. The imaging process may take time depending on the drive size. After completion, FTK Imager verifies the hash values automatically to maintain forensic integrity. Finally, the hash values should match.  

---

## Expected Output
- A `.mem` file containing RAM data.  
- A disk image file (e.g., `.E01` or `.dd`) in the selected destination.  
- Verified hash values confirming forensic integrity.  

---


