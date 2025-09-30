# Active-Directory-Practice

# Virtualization of Windows Server 2019 with Oracle VirtualBox  

## 1. Download Windows Server 2019  
- Go to the official Microsoft site: [Windows Server 2019 | Microsoft Evaluation Center](https://www.microsoft.com/en-us/evalcenter/download-windows-server-2019?msockid=3d127af2271d6df5282b6e7826a36cf8).  
- Select the **language** and download the appropriate **ISO** for your system.  

## 2. Create the Virtual Machine in VirtualBox  
1. Open **Oracle VirtualBox** and click **New**.  
2. Enter a **descriptive name** for the virtual machine (e.g., *Server2019-AD*).  
3. In **Type**, select: *Microsoft Windows*.  
4. In **Version**, choose: *Other Windows (64-bit)* or *Windows 2019 (64-bit)* if available.  
 <img src="https://i.imgur.com/qQ7ey0x.png" height="50%" width="60%"/>
5. Allocate at least **2 GB of RAM (2048 MB)**.  
<img src="https://i.imgur.com/SKVqnsy.png" height="50%" width="60%"/>
6. Click **Next** until the VM creation process is complete.  

## 3. Initial Configuration  
- Once created, the VM will appear in the VirtualBox list.  
<img src="https://i.imgur.com/7bPqsWh.png" height="50%" width="50%" />

## 4. Adjust Settings Before Starting  
Before starting the virtual machine, it is recommended to make the following adjustments:  

### Advanced Settings  
1. Select the VM and click **Settings**.  
2. Go to the **Advanced** tab.  
3. Change **Shared Clipboard** and **Drag'n Drop** to **Bidirectional**.  

### Network Settings  
To allow proper communication between the server, the host, and other virtual machines:  
1. In **Settings**, go to the **Network** tab.  
2. For **Adapter 1**, select **NAT**.
3. For **Adapter 2**, check **Enable Network Adapter**.  
   - For **Attached to**, select **Internal Network**.  
   - Enter a **name** for the internal network (e.g., *AD-Lab*)
## 5. Initial Configuration 
- Select it and click **Start**.  
- The system will prompt you to provide the path to the **Windows Server 2019 ISO** file you downloaded.  
- Load the ISO file and press **Mount and Retry Boot** to begin the installation.
  <img src="https://i.imgur.com/4IsA6u9.png" height="50%" width="60%"/>  

## 6. Operating System Installation  
- The installation wizard will launch automatically.  
- Follow the on-screen steps (this may take several minutes).  
- Once the installation is complete, you will have a **virtualized Windows Server 2019 environment** ready to configure **Active Directory**.  
