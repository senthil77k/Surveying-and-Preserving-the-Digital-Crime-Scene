# Surveying and Preserving the Digital Crime Scene

# Name:SENTHIL KUMARAN C
# Reg.no:212223220103

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


![Screenshot 2025-03-26 184953](https://github.com/user-attachments/assets/212bfbb3-be75-459b-bd10-ed7ebf4e3242)

- Enter a **Case Name** (e.g., `Autopsy1`).  
- Choose a **Case Folder** location.  
- Click **Next** → Click **Finish**.  


![Screenshot 2025-03-26 185459](https://github.com/user-attachments/assets/420dd98b-7999-41f0-9d5d-d487321d48f9)

### **Add the Virtual Disk as an Evidence Source**  
- Click **Add Data Source**  → **Select Host**


![Screenshot 2025-03-26 185619](https://github.com/user-attachments/assets/dadb0050-6e85-4d8c-a903-8d3a55bab2f5)

- Select **Local Disk** → **next** 

![Screenshot 2025-03-26 185635](https://github.com/user-attachments/assets/c109efbf-fa33-49d1-b371-ec9d7c75bc0c)


- Select Disk → **Choose the VHD drive (`Drive1`)**

![Screenshot 2025-03-26 190245](https://github.com/user-attachments/assets/270a0173-23a1-4b17-b23f-1a7e2d298506)

- Click **Next** → Keep default settings → Click **Finish**.  
- Wait for Autopsy to process the disk.  

### **Recover Deleted Files**  
- Go to **File Views** (left panel).  

![Screenshot 2025-03-26 190321](https://github.com/user-attachments/assets/2c2a5161-dd7f-473b-8881-65e01b5c5dad)

![Screenshot 2025-03-26 190331](https://github.com/user-attachments/assets/852d9604-1547-4550-8601-3fa7a612451c)

- Click **Deleted Files** → Find your deleted images.  
- Right-click an image → Click **Extract File**.  

![Screenshot 2025-03-26 190346](https://github.com/user-attachments/assets/d4aae3fe-aa89-4c99-92f3-e7286839eaf6)


- Select a folder to see the recovered files (e.g., `C:\forensic`).  
- Image is recovered successfully.


## Output :
### Folder before deleting the files

![Screenshot 2025-03-26 190356](https://github.com/user-attachments/assets/757aade6-4340-4e07-94ec-e6565e5eea6c)

### Folder after deleting the files

![Screenshot 2025-03-26 190401](https://github.com/user-attachments/assets/2e79cf2b-2e30-471f-97df-48631a1568f4)

### Folder after extracting the deleted images using autopsy
![Screenshot 2025-03-26 190407](https://github.com/user-attachments/assets/f71203f3-db69-4e53-8b46-41763dafdd79)


## Result:
Successfully extracted the deleted files from unallocated space using the Autospy tool.
