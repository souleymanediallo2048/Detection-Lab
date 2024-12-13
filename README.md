 # How to Install Ubuntu (Step by Step)

### Lab Objective:

The objective of this lab is to install Ubuntu 22.04 LTS on a VirtualBox virtual machine. By the end of this lab, you will understand how to set up and configure a virtual machine to run Ubuntu 22.04 as a guest OS.

### Skills Learned:

- Downloading and configuring VirtualBox for virtualization.
- Creating and configuring a virtual machine (VM).
- Installing Ubuntu 22.04 on a VM.
- Basic understanding of Ubuntu OS setup.

### Tools Used:

- **VirtualBox**: Virtualization platform for creating and running virtual machines.
- **Ubuntu 22.04 ISO**: Installation file for the Ubuntu operating system.
- **PC**: A physical machine with Windows, macOS, or Linux operating system.

---

### Step-by-Step Instructions

### Prerequisites:

- A computer with at least 4GB of RAM and 20GB of free disk space.
- Internet connection to download VirtualBox and Ubuntu ISO.# How to Install Ubuntu (Step by Step)

### Lab Objective:

The objective of this lab is to install Ubuntu 22.04 LTS on a VirtualBox virtual machine. By the end of this lab, you will understand how to set up and configure a virtual machine to run Ubuntu 22.04 as a guest OS.

### Skills Learned:

- Downloading and configuring VirtualBox for virtualization.
- Creating and configuring a virtual machine (VM).
- Installing Ubuntu 22.04 on a VM.
- Basic understanding of Ubuntu OS setup.

### Tools Used:

- **VirtualBox**: Virtualization platform for creating and running virtual machines.
- **Ubuntu 22.04 ISO**: Installation file for the Ubuntu operating system.
- **PC**: A physical machine with Windows, macOS, or Linux operating system.

---

### Step-by-Step Instructions

### Prerequisites:

- A computer with at least 4GB of RAM and 20GB of free disk space.
- Internet connection to download VirtualBox and Ubuntu ISO.
    
    ---
    

### Step 1: Download VirtualBox

- **Go to VirtualBox Website**:
    
    Navigate to the [VirtualBox official website](https://www.virtualbox.org/) and click on “Download.”
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/148d7db5-0306-4bb3-83c6-5023898dd3bd/image.png)
    
- **Download VirtualBox**:
    
    Select your operating system (Windows, macOS, or Linux) and download the installer.
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/c9a98401-4adc-4f98-819d-84e0ac193862/image.png)
    
- **Install VirtualBox**:
    
    Once downloaded, run the installer and follow the on-screen instructions. Stick with the default settings for installation.
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/7650d965-635f-405e-920c-2def861d533b/image.png)
    

<aside>
💡

- How to install VirtualBox (Step by Step)?
</aside>

---

### Step 2: Download Ubuntu 22.04 LTS ISO

- **Go to Ubuntu's Website**:
    
    Navigate to the [Ubuntu downloads page](https://ubuntu.com/download/server). Once there, scroll down to the “Alternative Downloads” section.
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/cb830b27-a619-49bd-821a-895c403597e2/image.png)
    
- **Select Ubuntu 22.04 LTS and Download**:
    
    On the "Alternative Downloads" section, navigate to "Previous releases" and locate version 22.04.5 LTS. Click on the download link to save the ISO file to your computer.
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/a53e42ba-27ba-4a12-a0a3-7be01a5ddbad/image.png)
    

---

### Step 3: Create a New Virtual Machine in VirtualBox

- **Open VirtualBox**:
    
    Launch VirtualBox after installation.
    
- **Click "New"**:
    
    Click the "New" button in the toolbar to create a new virtual machine.
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/3a4ce9b2-5179-4555-b2bd-095a62e0fe2d/image.png)
    
- **Provide Name and Operating System Type**:
    - **Name**: Enter a name like "Ubuntu 22.04".
    - **Type**: Select "Linux".
    - **Version**: Choose "Ubuntu (64-bit)" from the drop-down menu.
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/39f22398-fb62-411d-b6f9-da7ad2abcc66/image.png)
    
- **Set Memory Size**:
    
    Set the memory size. For Ubuntu, it's recommended to allocate at least **2048 MB (2 GB)** of RAM (more if your host machine has more resources).
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/65905e35-5715-47a9-9d91-9f3d16a925ac/image.png)
    
- **Create Virtual Hard Disk**:
    
    Select "Create a virtual hard disk now".
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/11d489d5-a231-4e2d-9124-71cc6f303448/image.png)
    
- **Specify Size of Hard Disk**:
    
    Set the size of the virtual hard disk. Allocate at least **20 GB** (adjust as per your needs), and click Next.
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/c6205270-5558-4bd4-85cd-aa247a7994e9/image.png)
    
- **Review and Finalize VM Configuration**
    
    After configuring the settings, you'll see a summary table displaying the configuration of your new virtual machine. Review the details to ensure everything is correct, then click "Finish" to complete the VM setup process.
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/611593c8-2a0a-48c6-a921-37ed476f0ebf/image.png)
    

---

### Step 4: Configure the Virtual Machine for Ubuntu Installation

- **Select the VM**:
    
    From the VirtualBox main window, select your newly created VM (e.g., "Ubuntu 22.04").
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/513d1567-640c-4054-b696-1ee5c2dabd7d/image.png)
    
- **Click "Settings"**:
    
    Click the "Settings" button in the toolbar to configure the virtual machine.
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/97c1c4d0-db29-4ae1-a2dd-f044b58f2cce/image.png)
    
- **Set System Settings**:
    - Under **System > Processor**, increase the number of CPUs to at least **2** if your host machine allows it.
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/ce01b308-c441-4bf2-845a-5e5c6910c1e6/image.png)
    
- **Storage Settings**:
    - Under **Storage**, click on the "Empty" CD/DVD icon under the "Controller: IDE" section.
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/184bf969-536f-4cf0-a5bd-679b91504cd4/image.png)
    
    - On the right, click on the "CD icon" and choose "Choose a disk file…".
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/9a138542-2f89-40a2-a790-37e26df6746b/image.png)
    
    - Browse and select the Ubuntu 22.04 ISO file you downloaded earlier.
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/edbf16d2-9e91-4c69-8c04-8538caba27cb/image.png)
    
- **Network Settings**:
    - Under **Network**, ensure "Attached to: NAT" is selected (default).
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/1948f06e-dc61-4d2f-9591-40726ca4b2ae/image.png)
    
- **Click OK**:
    
    Once these settings are configured, click **OK** to save.
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/4fac9fdf-1a89-45b2-bb72-9ead441002f2/image.png)
    

---

### Step 5:

- **Start the Virtual Machine**:
    
    From VirtualBox, select your VM and click **Start**.
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/dc73c12a-e6b6-4fe5-9fba-dc2df29981a0/image.png)
    
- **Boot from ISO**:
    
    The VM will start, and the Ubuntu installer should load from the ISO file.
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/0a8d90c6-d9b9-4004-8c19-67cb5f38cefd/image.png)
    
- **Choose Install Ubuntu**:
    
    Once the installer loads, choose "Try or Install Ubuntu" and hit Enter.
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/7003ea0c-d07d-4bc4-9427-bd735171f088/image.png)
    
- **Select your Language**:
    
    Select your language (default is English) and hit Enter.
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/7c41720a-9453-4eb5-bd67-18a6cf1078b3/image.png)
    
- **Updates and Other Software**:
    
    Choose "Continue Without Updating" as we want to install Ubuntu 22.04 and hit Enter.
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/43eb650e-c45d-4ba0-89d9-156d00c3a8c7/image.png)
    
- **Configure Keyboard**:
    
    Select your keyboard layout and Variant (default is English). With “Done” selected, hit Enter.
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/c26acd1b-47cf-423f-8afb-bc095433a78d/image.png)
    
- **Configure Ubuntu**:
    
    Select "Ubuntu Server". With “Done” selected, hit Enter.
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/e73f8a09-1f9e-41e0-9333-8db9b149141a/image.png)
    
    When prompted for Network Connections, Configure Proxy, and Configure Ubuntu Archive Mirror, simply select "Done" and press Enter for each option. We will be using the default settings throughout this process.
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/7e8bd8a3-2a7e-4ed6-adb7-2acca576d7d5/image.png)
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/1263e676-aaa9-43a0-9c86-cc7268db4168/image.png)
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/a141903c-1155-4a84-8239-fe4dcd2008cf/image.png)
    
    On the Guided Storage Configuration screen, navigate using the arrow keys to highlight "Done" and press Enter to proceed.
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/cdada3f1-abec-43e8-bf2b-1cc3e827af89/image.png)
    
    On the storage configuration screen, review the settings, then press Enter to select "Continue". When prompted to confirm the destructive action, select "Continue" again and press Enter to proceed with the installation.
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/13b9f7ad-aa04-47b4-accc-40b6893003c7/image.png)
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/f057f875-271c-4ce9-ab31-93966fe695db/image.png)
    
- **Create User Account**:
    
    Enter your name, a server name, username, and password. Click **Done**.
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/7415c995-b2bf-4a6a-b408-577ed2df4121/image.png)
    
- **Complete Installation**:
    
    On the upgrade to Ubuntu Pro screen, we will choose Skip for now and hit continue as we aim to install Ubuntu 22.04 LTS.
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/9e528b26-f834-42b8-9fdc-bda87ae65241/image.png)
    
    On the SSH Setup screen, check “Install OpenSSH server” to enable secure remote access
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/2d04f2af-cc74-4483-ad80-9c9a3fafdf56/image.png)
    
    On the Featured Server Snaps screen, use your arrow keys to navigate to "Done" and press Enter to proceed with the installation.
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/2308e438-d570-4f3f-9cbb-6c3dfb8c9870/image.png)
    
    The installation process will now begin. Ubuntu will be installed on your virtual machine, which may take several minutes to complete. During this time, you can monitor the progress on the screen.
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/611a9c3f-6843-4433-8046-e58d1c5e94aa/image.png)
    
- **Reboot**:
    
    Once the installation completes, click **Reboot Now** and remove the installation medium when prompted (VirtualBox will do this automatically).
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/569d4f7a-77bf-4e18-8567-134306b597ac/image.png)
    
    If you encounter a "Failed Unmounting /cdrom" error, simply press Enter to continue with the reboot process. This error is common and does not affect the installation.
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/d7479349-c701-4d73-bb2c-0167b395b37c/image.png)
    

---

### Step 6: Post-Installation Setup

- **Log in to Ubuntu**:
    
    After rebooting, you'll reach the Ubuntu login screen. Enter your password to log in.
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/8e87f2b4-3d35-4ded-bf72-07bacabefbe7/image.png)
    
- **Install Guest Additions**:
    
    For better performance, screen resolution, and integration between your host machine and the VM:
    
    - In VirtualBox, click **Devices** > **Insert Guest Additions CD image**.
    - Follow the on-screen prompts to install Guest Additions in Ubuntu.
- **Update the System**:
    
    Open the terminal in Ubuntu and run the following commands to update the system:
    
    ```bash
    sudo apt update
    sudo apt upgrade
    
    ```
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/e45d74d4-0ab9-47db-b660-c6d2d25be2fa/image.png)
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/12f4526c-33de-4aad-9746-23fc37df63fd/image.png)
    

---

### Conclusion:

You have successfully installed Ubuntu 22.04 on VirtualBox. You can now explore the Ubuntu operating system, run applications, and experiment with its features in a virtual environment.
    
    ---
    

### Step 1: Download VirtualBox

- **Go to VirtualBox Website**:
    
    Navigate to the [VirtualBox official website](https://www.virtualbox.org/) and click on “Download.”
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/148d7db5-0306-4bb3-83c6-5023898dd3bd/image.png)
    
- **Download VirtualBox**:
    
    Select your operating system (Windows, macOS, or Linux) and download the installer.
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/c9a98401-4adc-4f98-819d-84e0ac193862/image.png)
    
- **Install VirtualBox**:
    
    Once downloaded, run the installer and follow the on-screen instructions. Stick with the default settings for installation.
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/7650d965-635f-405e-920c-2def861d533b/image.png)
    

<aside>
💡

- How to install VirtualBox (Step by Step)?
</aside>

---

### Step 2: Download Ubuntu 22.04 LTS ISO

- **Go to Ubuntu's Website**:
    
    Navigate to the [Ubuntu downloads page](https://ubuntu.com/download/server). Once there, scroll down to the “Alternative Downloads” section.
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/cb830b27-a619-49bd-821a-895c403597e2/image.png)
    
- **Select Ubuntu 22.04 LTS and Download**:
    
    On the "Alternative Downloads" section, navigate to "Previous releases" and locate version 22.04.5 LTS. Click on the download link to save the ISO file to your computer.
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/a53e42ba-27ba-4a12-a0a3-7be01a5ddbad/image.png)
    

---

### Step 3: Create a New Virtual Machine in VirtualBox

- **Open VirtualBox**:
    
    Launch VirtualBox after installation.
    
- **Click "New"**:
    
    Click the "New" button in the toolbar to create a new virtual machine.
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/3a4ce9b2-5179-4555-b2bd-095a62e0fe2d/image.png)
    
- **Provide Name and Operating System Type**:
    - **Name**: Enter a name like "Ubuntu 22.04".
    - **Type**: Select "Linux".
    - **Version**: Choose "Ubuntu (64-bit)" from the drop-down menu.
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/39f22398-fb62-411d-b6f9-da7ad2abcc66/image.png)
    
- **Set Memory Size**:
    
    Set the memory size. For Ubuntu, it's recommended to allocate at least **2048 MB (2 GB)** of RAM (more if your host machine has more resources).
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/65905e35-5715-47a9-9d91-9f3d16a925ac/image.png)
    
- **Create Virtual Hard Disk**:
    
    Select "Create a virtual hard disk now".
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/11d489d5-a231-4e2d-9124-71cc6f303448/image.png)
    
- **Specify Size of Hard Disk**:
    
    Set the size of the virtual hard disk. Allocate at least **20 GB** (adjust as per your needs), and click Next.
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/c6205270-5558-4bd4-85cd-aa247a7994e9/image.png)
    
- **Review and Finalize VM Configuration**
    
    After configuring the settings, you'll see a summary table displaying the configuration of your new virtual machine. Review the details to ensure everything is correct, then click "Finish" to complete the VM setup process.
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/611593c8-2a0a-48c6-a921-37ed476f0ebf/image.png)
    

---

### Step 4: Configure the Virtual Machine for Ubuntu Installation

- **Select the VM**:
    
    From the VirtualBox main window, select your newly created VM (e.g., "Ubuntu 22.04").
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/513d1567-640c-4054-b696-1ee5c2dabd7d/image.png)
    
- **Click "Settings"**:
    
    Click the "Settings" button in the toolbar to configure the virtual machine.
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/97c1c4d0-db29-4ae1-a2dd-f044b58f2cce/image.png)
    
- **Set System Settings**:
    - Under **System > Processor**, increase the number of CPUs to at least **2** if your host machine allows it.
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/ce01b308-c441-4bf2-845a-5e5c6910c1e6/image.png)
    
- **Storage Settings**:
    - Under **Storage**, click on the "Empty" CD/DVD icon under the "Controller: IDE" section.
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/184bf969-536f-4cf0-a5bd-679b91504cd4/image.png)
    
    - On the right, click on the "CD icon" and choose "Choose a disk file…".
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/9a138542-2f89-40a2-a790-37e26df6746b/image.png)
    
    - Browse and select the Ubuntu 22.04 ISO file you downloaded earlier.
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/edbf16d2-9e91-4c69-8c04-8538caba27cb/image.png)
    
- **Network Settings**:
    - Under **Network**, ensure "Attached to: NAT" is selected (default).
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/1948f06e-dc61-4d2f-9591-40726ca4b2ae/image.png)
    
- **Click OK**:
    
    Once these settings are configured, click **OK** to save.
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/4fac9fdf-1a89-45b2-bb72-9ead441002f2/image.png)
    

---

### Step 5:

- **Start the Virtual Machine**:
    
    From VirtualBox, select your VM and click **Start**.
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/dc73c12a-e6b6-4fe5-9fba-dc2df29981a0/image.png)
    
- **Boot from ISO**:
    
    The VM will start, and the Ubuntu installer should load from the ISO file.
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/0a8d90c6-d9b9-4004-8c19-67cb5f38cefd/image.png)
    
- **Choose Install Ubuntu**:
    
    Once the installer loads, choose "Try or Install Ubuntu" and hit Enter.
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/7003ea0c-d07d-4bc4-9427-bd735171f088/image.png)
    
- **Select your Language**:
    
    Select your language (default is English) and hit Enter.
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/7c41720a-9453-4eb5-bd67-18a6cf1078b3/image.png)
    
- **Updates and Other Software**:
    
    Choose "Continue Without Updating" as we want to install Ubuntu 22.04 and hit Enter.
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/43eb650e-c45d-4ba0-89d9-156d00c3a8c7/image.png)
    
- **Configure Keyboard**:
    
    Select your keyboard layout and Variant (default is English). With “Done” selected, hit Enter.
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/c26acd1b-47cf-423f-8afb-bc095433a78d/image.png)
    
- **Configure Ubuntu**:
    
    Select "Ubuntu Server". With “Done” selected, hit Enter.
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/e73f8a09-1f9e-41e0-9333-8db9b149141a/image.png)
    
    When prompted for Network Connections, Configure Proxy, and Configure Ubuntu Archive Mirror, simply select "Done" and press Enter for each option. We will be using the default settings throughout this process.
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/7e8bd8a3-2a7e-4ed6-adb7-2acca576d7d5/image.png)
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/1263e676-aaa9-43a0-9c86-cc7268db4168/image.png)
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/a141903c-1155-4a84-8239-fe4dcd2008cf/image.png)
    
    On the Guided Storage Configuration screen, navigate using the arrow keys to highlight "Done" and press Enter to proceed.
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/cdada3f1-abec-43e8-bf2b-1cc3e827af89/image.png)
    
    On the storage configuration screen, review the settings, then press Enter to select "Continue". When prompted to confirm the destructive action, select "Continue" again and press Enter to proceed with the installation.
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/13b9f7ad-aa04-47b4-accc-40b6893003c7/image.png)
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/f057f875-271c-4ce9-ab31-93966fe695db/image.png)
    
- **Create User Account**:
    
    Enter your name, a server name, username, and password. Click **Done**.
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/7415c995-b2bf-4a6a-b408-577ed2df4121/image.png)
    
- **Complete Installation**:
    
    On the upgrade to Ubuntu Pro screen, we will choose Skip for now and hit continue as we aim to install Ubuntu 22.04 LTS.
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/9e528b26-f834-42b8-9fdc-bda87ae65241/image.png)
    
    On the SSH Setup screen, check “Install OpenSSH server” to enable secure remote access
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/2d04f2af-cc74-4483-ad80-9c9a3fafdf56/image.png)
    
    On the Featured Server Snaps screen, use your arrow keys to navigate to "Done" and press Enter to proceed with the installation.
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/2308e438-d570-4f3f-9cbb-6c3dfb8c9870/image.png)
    
    The installation process will now begin. Ubuntu will be installed on your virtual machine, which may take several minutes to complete. During this time, you can monitor the progress on the screen.
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/611a9c3f-6843-4433-8046-e58d1c5e94aa/image.png)
    
- **Reboot**:
    
    Once the installation completes, click **Reboot Now** and remove the installation medium when prompted (VirtualBox will do this automatically).
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/569d4f7a-77bf-4e18-8567-134306b597ac/image.png)
    
    If you encounter a "Failed Unmounting /cdrom" error, simply press Enter to continue with the reboot process. This error is common and does not affect the installation.
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/d7479349-c701-4d73-bb2c-0167b395b37c/image.png)
    

---

### Step 6: Post-Installation Setup

- **Log in to Ubuntu**:
    
    After rebooting, you'll reach the Ubuntu login screen. Enter your password to log in.
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/8e87f2b4-3d35-4ded-bf72-07bacabefbe7/image.png)
    
- **Install Guest Additions**:
    
    For better performance, screen resolution, and integration between your host machine and the VM:
    
    - In VirtualBox, click **Devices** > **Insert Guest Additions CD image**.
    - Follow the on-screen prompts to install Guest Additions in Ubuntu.
- **Update the System**:
    
    Open the terminal in Ubuntu and run the following commands to update the system:
    
    ```bash
    sudo apt update
    sudo apt upgrade
    
    ```
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/e45d74d4-0ab9-47db-b660-c6d2d25be2fa/image.png)
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9c22527-bd10-481e-9b3a-c4bb8345e827/12f4526c-33de-4aad-9746-23fc37df63fd/image.png)
    

---

### Conclusion:

You have successfully installed Ubuntu 22.04 on VirtualBox. You can now explore the Ubuntu operating system, run applications, and experiment with its features in a virtual environment.
