

# Reviewing-Unallocated-Space-Extracting-Data-with-Tools-Digital-Investigation-Processes
## AIM:
To review unallocated space in a disk image, extract data using forensic tools, and understand the digital investigation process.

## DESIGN STEPS:
### Step 1:
Use tools like Autopsy or Sleuth Kit (blkls, icat) to identify and analyze unallocated space.

### Step 2:
Extract data from unallocated space and examine for hidden or deleted content.

### Step 3:
Document and interpret findings as part of the digital investigation process.

## PROGRAM:
Data Extraction and Investigation Tool Usage
```
lsblk
```

```
sudo dd if=/dev/sda of=/home/kali/disk.img bs=512
```

```
mmls ~/disk.img
```
```
sudo ls -lh disk.img
```
```
strings disk.img | less
```
## OUTPUT:
Unallocated Space Analysis and Extracted Data Report
![image](https://github.com/user-attachments/assets/754dee37-bef7-4cbf-b6c1-6bf8983befda)

![image](https://github.com/user-attachments/assets/a8b59831-7bd7-4699-8f56-ca192d17d70e)


![image](https://github.com/user-attachments/assets/3a0d7674-9182-4b14-aa62-1e76725d975a)


![image](https://github.com/user-attachments/assets/f759788f-0b11-4287-8db9-d0ab5a349d73)


![image](https://github.com/user-attachments/assets/6566bb2d-f19e-42d6-ac88-d6562f34117d)


## RESULT:
The unallocated space was successfully analyzed, data was extracted, and the digital investigation process was followed effectively.

