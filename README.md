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
5. Allocate at least **2 GB of RAM (2048 MB)**.  
6. Click **Next** until the VM creation process is complete.  

## 3. Initial Configuration  
- Once created, the VM will appear in the VirtualBox list.  
- Select it and click **Start**.  
- The system will prompt you to provide the path to the **Windows Server 2019 ISO** file you downloaded.  
- Load the ISO file and press **Start** to begin the installation.  

## 4. Operating System Installation  
- The installation wizard will launch automatically.  
- Follow the on-screen steps (this may take several minutes).  
- Once the installation is complete, you will have a **virtualized Windows Server 2019 environment** ready to configure **Active Directory**.  
