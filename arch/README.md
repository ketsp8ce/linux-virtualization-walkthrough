# Arch Linux Setup
You should now be ready to create a virtual machine and mount the Arch Linux ISO file. I will walk you through each step. 

---

## 🌀 Virtual machine Configuration
**Use the following screenshots as a guide. Click new, and configure the vm specs using these images as a guide. If you have specific plans for your memory, disk space, processors etc feel free to change things. If you are unsure what all of this means, just copy the values shown in the images and this will give you a basic setup for learning arch.

---

### ✅ Create New VM
 - Create a new virtual machine. 
![Create New VM](images/arch/step1.png)

### ✅ VM Name And OS
 - Fill in the rest of the values as shown.
![Configuration Step 1](images/arch/config1.png)

If you cannot view the image, copy the following values:
 - Name: ArchLinux 
 - Folder: select the default
 - ISO Imagine: Click other, and select the ISO file from your machine. 
 - Type: Linux
 - Subtype: ArchLinux
 - Version: Arch Linux (64 bit)

Under the ISO image text box, click the expanding arrow. Fill in the following values:

### ✅ Hardware
On the next screen:
 - Select a base memory of 8GB or 8192MB
 - Set processors to 4
Do NOT check "enable EFI"
![Configuration Step 2](images/arch/config2.png)

### ✅ Virtual Hard Disk
 - Check "Create a Virtual Hard Disk Now" and set disk size to 16.00GB
![Configuration Step 3](images/arch/config3.png)

### ✅ Summary
 - Read over the summary, then click finish!
![Configuration Step 4](images/arch/config4.png)

---

## 🌀 Setting up Arch OS
You should see the start script run on the screen
![Arch Start Terminal](images/arch/start.png)
We will now enter the main menu and configure the setup of the OS 

### ✅ Select Language
 - Select a language
![Select Language](images/arch/select_language.png)

### ✅ Main Menu
This is the main menu
![Main Menu](images/arch/main_menu1.png)

** from here, i will use a notation to let you know what to select rather then screenshotting each individual step. There will also be some open endedness in your options.

Mirrors and repositories - Select region (insert country here)
Mirrors and repositories - Optional repositories (multilib) - back
Disc configuration - Partitioning - Use a best-effort default partition layout - (enter) - btrfs - no - Use Compression - back
Authentication - user account - add a user - (insert username here) - (insert password here) - (confirm password) - yes - confirm and exit - back
Profile - type - desktop - (Pick your favorite) - back
Applications - Audio - (Choose) - back
Network Configuration - Use NetworkManager - back
Timezone - (select your timezone) - back
Install - Yes

