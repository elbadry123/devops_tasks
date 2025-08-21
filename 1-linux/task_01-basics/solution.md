# Task 1 - Linux Basics

## User Management
```bash
# Add user
sudo adduser mohamed

# Delete user
sudo userdel -r mohamed
File Management
bash
Copy
Edit
# Create file
touch abdullahf

# Change file permissions
chmod 644 abdullahf
chmod u=rw,g=r,o=r abdullahf

# Create and remove folder
mkdir abdullahfolder
rmdir abdullahfolder

# Search for file/folder
find / -name "abdullahf"
find . -name "abdullahfolder"
File Editing
bash
Copy
Edit
# Edit file with vim
vim ziad

# Edit another file
vim ahmed

# View file contents
cat ahmed
Date and Aliases
bash
Copy
Edit
# Show current date
date

# Create alias for date
alias d=date

# Use alias
d
Directory & File Operations
bash
Copy
Edit
# Create folder and file
mkdir rabia
cd rabia
touch dalia

# Create another folder
cd /home
mkdir engy
cd engy

# Copy file
cp ../rabia/dalia .

# Create new file and move it
touch mazen
mv mazen /home/rabia/

# Rename file
cd /home/rabia
mv mazen samir

# Show file content
cat samir
