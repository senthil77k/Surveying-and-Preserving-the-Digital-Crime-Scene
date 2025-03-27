# Surveying and Preserving the Digital Crime Scene

Name:ROHAN J
Reg.no:212223O40171

## **Aim:**
Data recovery from unallocated space, using forensic tools(Autospy) to extract and analyze data.

## **Implementation steps:**

### **1. Copy Files to the Virtual Disk**  
- Open **File Explorer** → Go to the new drive (`C: or D:`), where the folder created in the New Virtual Disk
- Create a new folder (`Autospy`) and copy **images or files** into it.  

### **2. Delete the Files**  
- Select any one or two images → Press **Delete**.  
- Empty the **Recycle Bin** to permanently delete them.  

### **3. Recover Deleted Files Using Autopsy**  
### **Open Autopsy & Create a New Case** 

- Launch **Autopsy** and **Run as a administrator**  
- Click **Create New Case**.  


![Screenshot 2025-03-22 113352](https://github.com/user-attachments/assets/d7b6b0e4-9bf1-4180-8f08-bd982e7156a7)


- Enter a **Case Name** (e.g., `Autopsy1`).  
- Choose a **Case Folder** location.  
- Click **Next** → Click **Finish**.  


![Screenshot 2025-03-26 185459](https://github.com/user-attachments/assets/420dd98b-7999-41f0-9d5d-d487321d48f9)

### **Add the Virtual Disk as an Evidence Source**  
- Click **Add Data Source**  → **Select Host**


![Screenshot 2025-03-26 185619](https://github.com/user-attachments/assets/dadb0050-6e85-4d8c-a903-8d3a55bab2f5)

- Select **Local Disk** → **next** 

![Screenshot 2025-03-22 105903](https://github.com/user-attachments/assets/bd9c7f9b-bb13-417a-a556-1e12c8918e69)



- Select Disk → **Choose the VHD drive (`Drive1`)**

![Screenshot 2025-03-27 142633](https://github.com/user-attachments/assets/3f1e66a8-97c7-4ded-b065-daae247385e4)


- Click **Next** → Keep default settings → Click **Finish**.  
- Wait for Autopsy to process the disk.  

### **Recover Deleted Files**  
- Go to **File Views** (left panel).  

![Screenshot 2025-03-26 190321](https://github.com/user-attachments/assets/2c2a5161-dd7f-473b-8881-65e01b5c5dad)



- Click **Deleted Files** → Find your deleted images.  
- Right-click an image → Click **Extract File**.  
![Screenshot 2025-03-27 142738](https://github.com/user-attachments/assets/ba543902-eb59-45bd-896d-cab60cbe9ddc)





- Select a folder to see the recovered files (e.g., `C:\forensic`).  
- Image is recovered successfully.


## Output :
### Folder before deleting the files

![Screenshot 2025-03-27 142807](https://github.com/user-attachments/assets/b1f78713-1156-4d05-be29-52daf1cdfad0)


### Folder after deleting the files

![Screenshot 2025-03-22 105704](https://github.com/user-attachments/assets/9928a730-ddd8-4374-b28b-d1ed73af812a)


### Folder after extracting the deleted images using autopsy
![Screenshot 2025-03-27 142807](https://github.com/user-attachments/assets/bb49a142-6dca-4ec8-b142-5868ef0d4b5e)




## Result:
Successfully extracted the deleted files from unallocated space using the Autospy tool.
