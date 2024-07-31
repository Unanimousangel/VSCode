
# VSCode-Extensions

Installation guide on how to download extensions to VSCode offline
---
## VSCode Update
[Download](https://code.visualstudio.com/download) version 1.90.02 of VsCode 
+ Windows will use x32 
  
  1. Go to downloads and double click the file to run the installer.
  
  2.  You will be greeted by a EULA i hit i acept the agreement and then hit next. <br>
![image](https://github.com/Unanimousangel/VSCode/assets/71099427/2ff53d1c-bdf0-41fa-9a95-04cc8f43e0d4)

  
  3.  On the next page leave "Register code a an editor for supported file types, and Add to PATH checked, then hit next. <br>
      ![image](https://github.com/Unanimousangel/VSCode/assets/71099427/131a2993-a1dc-4a38-989a-a660bae31ff2)

  4. Hit install and VsCode will start installing on the machine.
  5. Once VSCode is done installing, check the version number by hitting and about validate that it says version 1.90.2. as shown below  <br>
![image](https://github.com/Unanimousangel/VSCode/assets/71099427/5d7728ac-e87a-487c-b217-1cbe4fbddcdc)

+ Linux will use .rpm for red hat
  1. On your Red Hat Linux machine, navigate to the directory where you transferred the RPM file.
  2. Install the RPM package using the rpm command. 
  `sudo rpm -Uvh code-1.90.2-1718751675.el8.x86_64.rpm` 
  3. Validate that VSCode is on the right version by clicking on help and about, as we did on windows.
---
## VSCode-extensions
### Before installing the following, [install](https://dotnet.microsoft.com/en-us/download/dotnet/8.0) .net 8.0 SDK version 8.0.302 x32 version.
+ Windows
  1. Double click on the file after downloading the x32 windows version, hit install and accept on the UAC it will  download shortly after. <br>
    ![image](https://github.com/Unanimousangel/VSCode/assets/71099427/a38d3db8-7683-4a78-84e6-8734ffa02274)
  2. After instillation, [Download](https://www.nuget.org/packages/Microsoft.dotnet-interactive) the NuGet dotnet-interactive package. After downloading, run the command `dotnet.exe tool install --global Microsoft.dotnet-interactive --add-source <path/to/folder/that/has/nuget/package> --version <dotnet-interactive-version>` <br>
  ![image](https://github.com/user-attachments/assets/1ddf1365-eb57-4ef2-94d4-f3b2ada0acd5)


  3. Restart VSCode
  4. Hit `CTRL+SHIFT+P to launch the command pallete`
  5. select the option `Notebook: Select Notebook Kernel` > `Select Another Kernel` > `.Net Interactive`
# All of the following extensions will be installed from VSIX
1. On windows or linux click on extensions
2. Hit The elipses
3. Install from VSIX
4. Install the appropriate packages based on the versions of VSCode Below. <br>
![image](https://github.com/user-attachments/assets/d5e74959-d000-48cd-a30d-e9f4ae148d12) <br>
![image](https://github.com/user-attachments/assets/8956a121-4eb3-43e5-8d59-277b6d00b732)


## *Universal are listed in case you want to download on your own, howeverer all the files are available in a zip file with there respective OS*
##  vscode-v1.59.1

 + Linux
    + .net extension pack | Version 1.0.13
    + .net install tool | Version 2.0.6
    + Markdown all in one | Version 3.6.2
    + Polygot notebooks | Version 1.0.5229040

  + Windows
    + .net extension pack | Version 1.0.13
    + .net install tool | Version 2.0.6
    + Markdown all in one | Version 3.6.2
    + Polygot notebooks | Version 1.0.5229040
    + PowerShell | Version 2024.3F.2

  + Universal
    + .net extension pack | Version 1.0.13
    + .net install tool | Version 2.0.6
    + Markdown all in one | Version 3.6.2
    + Polygot notebooks | Version 1.0.5229040

## vscode-v1.79.1
  + Linux
    + .net extension pack | Version 1.0.13
    + .net install tool | Version 2.0.6
    + Markdown all in one | Version 3.6.2
    + Polygot notebooks | Version 1.0.5229040
  
  + Windows
    + .net extension pack | Version 1.0.13
    + .net install tool | Version 2.06
    + Markdown all in one | Version 3.6.2
    + Polygot notebooks | Version 1.0.5229040
    + PowerShell | Version 2024.3.2

   
  + Universal
    + .net extension pack | Version 1.0.13
    + .net install tool | Version 2.0.6
    + Markdown all in one | Version 3.6.2
    + Polygot notebooks | Version 1.0.5229040
  
## vscode-v1.90.2
  + Linux
    + Jupter | Version 2024.6.2024070901
    + .net extension pack | Version 1.0.13
    + .net install tool | Version 2.0.7
    + Jupyter cell tags | Version  0.1.9
    + Jupyter keymap | Version 1.1.2
    + Jupyter notebook renderers | Version 1.0.18
    + Jupyter slide show | Version  0.1.6
    + Markdown all in one | Version 3.6.2
    + Polygot notebooks | Version 1.0.5367011
  
  + Windows
    + Jupter | Version 2024.6.2024070901
    + .net extension pack | Version 1.0.13
    + .net install tool | Version 2.0.7
    + Jupyter cell tags | Version  0.1.9
    + Jupyter keymap | Version 1.1.2
    + Jupyter notebook renderers | Version 1.0.18
    + Jupyter slide show | Version  0.1.6
    + Markdown all in one | Version 3.6.2
    + Polygot notebooks | Version 1.0.5367011
    + PowerShell | Version 2024.3.2 
  
  + Universal
    + .net extension pack | Version 1.0.13
    + .net install tool | Version 2.0.7
    + Markdown all in one | Version 3.6.2
    + Polygot notebooks | Version 1.0.5367011
















