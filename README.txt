!!!!!!Make sure your login details are set correctly using the "git config --list" command!!!!!!


IMPORTING(Only needs to be done once)

1. Select desired local directory
PowerShell/Bash:
2. cd <local-directory-address>
3. git clone https://github.com/nwbester/CMPG213-Group-5




EXPORTING(Every time you make a major change)

1. Save all files locally
Powershell/Bash:
2. git remote add origin https://github.com/nwbester/CMPG213-Group-5.git
3. git branch -M main/<branch name>
4. git add <file to be committed>(repeat for all necessary files)
5. git commit -m "<Comment/Dev Notes>"
6. git push -u origin main
