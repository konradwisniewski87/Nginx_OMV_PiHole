# NGINX Configuration

### Repository include configuration for:
-  OpenMediaVault
-  PiHole


| Program      | Version      |
| ------------- | ------------- |
| Nginx | 1.18.0 |
| Pihole | 5.18.3 |
| OMV | 6.9.16-1 (Shaitan) |
| PHP-FPM | 7.4 |
| FTL | 5.25.2 |

<h2> Server is based on the Raspbian Light </h2>

<br>
<br>

## Simple way to connect to this and another server from windows 11\10:
### by shorcut:
1. Right click anywhere on the desktop -> New -> Shortcut
2. Type 
```
WT -p "Windows PowerShell" ssh USER@HOSTNAME; new-tab -p "Windows PowerShell" ssh USER@HOSTNAME -p 22
```
\* -p 22, it's port, this parameters is not require

### by *.cmd file:
1. Right click anywhere on the desktop -> New -> Rich Text
2. Delete name and extension
3. Type name e.g. nas_nas2.cmd
4. Paste: 
    ```
    start WT -p "Windows PowerShell" ssh USER@HOSTNAME; new-tab -p "Windows PowerShell" ssh USER@HOSTNAME -p 22
    ```
\* -p 22, it's port, this parameters is not require

Where:
| Command      | Description      |
| ------------- | ------------- |
| WT | open windows terminal |
| new-tab | open new tab |
| split-panel | splits the screen |
| -p | specifies the profile for example "Windows PowerShell", "Ubuntu" |
| -d | specific starting directory |