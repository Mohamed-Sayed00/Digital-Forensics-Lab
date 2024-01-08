# Digital-Forensics-Lab

# Build Your Forensic Workstation​
1) download Windows Server 2019 vm [her](https://www.microsoft.com/en-us/evalcenter/evaluate-windows-server-2019).
2) Download VirtualBox [her](https://www.virtualbox.org/wiki/Downloads)
4) Install a new Windows VM 
5) Enable Windows Subsystem for Linux (WSL)
  > Open PowerShell as Administrator and run the following command:

``Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Windows-Subsystem-Linux``

7) Download the Ubuntu Distribution [her](https://learn.microsoft.com/en-us/windows/wsl/install-manual#downloading-distributions)
6) Install Ubuntu
>When downloaded, rename the package from .appxbundle to .zip and extract the archive
>
>Install the x64.appx package contained within the archive using the followingPowerShell command (as administrator!):

`Add-AppxPackage .\Ubuntu_2004.4.2.0_x64.appx`

7)  Configure the Windows Environment
   
    - Set the time zone to UTC – important!
    - Open File Explorer -> View -> check “Hidden items” and “File name extensions”.
    - Create a “C:\Cases” and a “C:\Tools” folder
    - Configure Microsoft Defender to avoid interference with evidence or tools.
      
8) Download and Install Forensic Tools
  * download tools
     - arsenal image [her](https://arsenalrecon.com/downloads/)
     - kape [her](https://www.kroll.com/en/services/cyber-risk/incident-response-litigation-support/kroll-artifact-parser-extractor-kape)
     - regripper log explorer [her](https://github.com/keydet89/RegRipper3.0)
     - notepad++ [her](https://notepad-plus-plus.org/)
     - event log explorer [her](https://eventlogxp.com/)
     - ezTools [her](https://ericzimmerman.github.io/#!index.md)
     - firefox [her](https://www.mozilla.org/en-US/firefox/new/)
  * copy tools to tools folder
  * install tools
      - event log explorer
      - ezTools
      - notebad++
