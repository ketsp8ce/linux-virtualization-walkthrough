# Arch Linux Setup
You should now be ready to create a virtual machine and mount the Arch Linux ISO file. I will walk you through each step. 

---

## 🌀 Virtual Machine Configuration
**Use the following screenshots as a reference. Click New, and configure the VM specifications using these images as a guide. If you have specific plans for your memory, disk space, processors etc feel free to change things. If you are unsure what all of this means, just copy the values shown in the images and this will give you a basic setup for learning arch.**

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
 - ISO Image: Click **Other**, and select the ISO file from your machine. 
 - Type: Linux
 - Subtype: ArchLinux
 - Version: Arch Linux (64 bit)

Under the ISO image text box, click the expanding arrow. Fill in the following values:

### ✅ Hardware
On the next screen:
 - Select a base memory of 8GB or 8192MB
 - Set processors to 4
Do **not** check 'Enable EFI'
![Configuration Step 2](images/arch/config2.png)

### ✅ Virtual Hard Disk
 - Select **Create a Virtual Hard Disk Now** and set disk size to 16.00GB
![Configuration Step 3](images/arch/config3.png)

### ✅ Summary
 - Review the summary, then click **Finish**!
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

### ✅ Setup Instructions
From here, I will use shorthand notation to show you what to select rather than screenshotting each individual step. Some choices will be open-ended depending on your preferences.

**Mirrors and repositories** → **Select region** (insert your country)  
**Mirrors and repositories** → **Optional repositories (multilib)** → **Back**  

**Disk configuration** → **Partitioning** → **Use best-effort default partition layout** → (Enter) → **btrfs** → **No** → **Use Compression** → **Back**  

**Authentication** → **User account** → **Add a user** → (insert username) → (insert password) → (confirm password) → **Yes** → **Confirm and exit** → **Back**  

**Profile** → **Type** → **Desktop** → (pick your favorite) → **Back**  

**Applications** → **Audio** → (choose your preference) → **Back**  

**Network Configuration** → **Use NetworkManager** → **Back**  

**Timezone** → (select your timezone) → **Back**  

**Install** → **Yes**


### ✅ Done
After completion, you should restart the virtual machine. The script will run in your terminal and install Arch Linux with a graphical desktop environment.

