# Using-the-Autopsy-retrieve-the-deleted-files
# AIM:
To use Autopsy in Kali Linux to retrieve and analyze deleted files from a disk image.

# DESIGN STEPS:
# Step 1:
Open Autopsy and create a new case with appropriate case details.

# Step 2:
Add a disk image as a data source and let Autopsy analyze the content.

# Step 3:
Navigate to the "Deleted Files" section in Autopsy and examine or recover the deleted files.

# PROGRAM:
1. Copy Files to the Virtual Disk
.Open File Explorer → Go to the new drive (C: or D:), where the folder created in the New Virtual Disk
.Create a new folder (Autospy) and copy images or files into it.

2. Delete the Files
.Select any one or two images → Press Delete.
.Empty the Recycle Bin to permanently delete them.

3. Recover Deleted Files Using Autopsy
# Open Autopsy & Create a New Case
.Launch Autopsy and Run as a administrator

Click Create New Case.

![image](https://github.com/user-attachments/assets/db50c3f2-c2f1-4b29-9139-5ed2e566bad8)


.Enter a Case Name (e.g., Autopsy1).

.Choose a Case Folder location.

.Click Next → Click Finish.

![image](https://github.com/user-attachments/assets/febe58ac-2645-463c-8a46-f98b37188a37)


# Add the Virtual Disk as an Evidence Source

.Click Add Data Source → Select Host 

![image](https://github.com/user-attachments/assets/af9fe3a8-c92c-4cd7-9b9d-dc9fb4cc7464)


.Select Local Disk → next 

![image](https://github.com/user-attachments/assets/b5e1f7d6-6126-41a5-8c82-fa79006f66cb)


.Select Disk → Choose the VHD drive (Drive1)

![image](https://github.com/user-attachments/assets/ae20226d-6207-4de9-862c-bb93e1f05ca9)


.Click Next → Keep default settings → Click Finish.
.Wait for Autopsy to process the disk.

# Recover Deleted Files

.Go to File Views (left panel).

![image](https://github.com/user-attachments/assets/e7858b4a-7ecc-4c69-815f-632fa233bbc1)

![image](https://github.com/user-attachments/assets/f41a2eaa-9b7d-4d72-b12b-f6746f058598)


.Click Deleted Files → Find your deleted images.

.Right-click an image → Click Extract File.

![image](https://github.com/user-attachments/assets/edd1b8ec-0fee-4ca8-b30e-44ebfa7755a3)


.Select a folder to see the recovered files (e.g., C:\forensic).

.Image is recovered successfully.



# Output :
.Folder before deleting the files

![image](https://github.com/user-attachments/assets/415fcba3-b4d0-483b-baca-a8abe2123481)


.Folder after deleting the files

![image](https://github.com/user-attachments/assets/7c40846b-c856-41a9-8900-8ea8d9a8d3a3)


# Folder after extracting the deleted images using autopsy

![image](https://github.com/user-attachments/assets/6f85b8b3-abdb-4538-a492-d8f90e28688b)


RESULT:
Deleted files were successfully retrieved and analyzed using Autopsy.
