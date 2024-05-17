# All basic Linux Commands that help you to become linux coder within 2 mins

# List directory contents
ls

# Change the current directory
cd /path/to/directory

# Print working directory
pwd

# Make directories
mkdir new_directory

# Remove empty directories
rmdir empty_directory

# Remove files or directories
rm file.txt
rm -r directory

# Copy files and directories
cp source_file destination_file
cp -r source_directory destination_directory

# Move or rename files and directories
mv old_name new_name
mv file.txt /new/location/

# Create an empty file or update the timestamp of a file
touch newfile.txt

# Concatenate and display file content
cat file.txt

# View file content one screen at a time
less file.txt

# View file content one screen at a time
more file.txt

# Display the first few lines of a file
head file.txt
head -n 10 file.txt

# Display the last few lines of a file
tail file.txt
tail -n 10 file.txt

# Display a line of text
echo "Hello, World!"

# Display the manual for a command
man ls

# Search text using patterns
grep "pattern" file.txt

# Search for files in a directory hierarchy
find /path -name "filename"

# Find files by name
locate filename

# Estimate file space usage
du -h /path

# Report file system disk space usage
df -h

# Change file modes or Access Control Lists
chmod 755 file.txt

# Change file owner and group
chown user:group file.txt

# Make links between files
ln -s target link_name

# Report a snapshot of current processes
ps aux

# Display Linux tasks
top

# Interactive process viewer
htop

# Send a signal to a process
kill process_id

# Kill processes by name
killall process_name

# Look up or signal processes based on name and other attributes
pkill process_name

# Resume a suspended job in the background
bg job_id

# Bring a background job to the foreground
fg job_id

# List active jobs
jobs

# Locate a command
which command_name

# Create an alias for a command
alias ll='ls -la'

# Remove an alias
unalias ll

# Simple text editor
nano file.txt

# Powerful text editor
vi file.txt

# Improved vi editor
vim file.txt

# Extensible, customizable text editor
emacs file.txt

# Non-interactive network downloader
wget http://example.com/file.txt

# Transfer data from or to a server
curl http://example.com

# Send ICMP ECHO_REQUEST to network hosts
ping example.com

# Print the route packets take to the network host
traceroute example.com

# Print network connections, routing tables, interface statistics, masquerade connections, and multicast memberships
netstat -tuln

# Utility to investigate sockets
ss -tuln

# Administration tool for IPv4 packet filtering and NAT
sudo iptables -L

# Uncomplicated Firewall, frontend for iptables
sudo ufw enable

# OpenSSH remote login client
ssh user@host

# Secure copy (remote file copy program)
scp file.txt user@host:/path

# Remote file and directory synchronization
rsync -avz source destination

# Archive files
tar -cvf archive.tar file.txt
tar -xvf archive.tar

# Package and compress (archive) files
zip archive.zip file.txt

# List, test, and extract compressed files in a ZIP archive
unzip archive.zip

# Compress files
gzip file.txt

# Decompress files
gunzip file.txt.gz

# Compress files
bzip2 file.txt

# Decompress files
bunzip2 file.txt.bz2

# Compress files
xz file.txt

# Decompress files
unxz file.txt.xz

# Advanced Package Tool (for Debian-based systems)
sudo apt update
sudo apt install package_name

# Package manager for RPM-based distributions
sudo yum update
sudo yum install package_name

# Next generation package manager for RPM-based distributions
sudo dnf update
sudo dnf install package_name

# Package manager utility for Arch Linux
sudo pacman -Syu
sudo pacman -S package_name

# RPM Package Manager
sudo rpm -ivh package.rpm

# Debian package manager
sudo dpkg -i package.deb

# Package management system for Ubuntu
sudo snap install package_name

# System for building, distributing, and running sandboxed desktop applications on Linux
flatpak install package_name

# Docker container command
docker run image_name

# Control the systemd system and service manager
sudo systemctl start service
sudo systemctl stop service

# Query and display messages from the journal
sudo journalctl -xe

# Time-based job scheduler
crontab -e

# Schedule commands to run at a particular time
echo "command" | at now + 5 minutes

# Pattern scanning and processing language
awk '/pattern/ {print $0}' file.txt

# Stream editor for filtering and transforming text
sed 's/old/new/g' file.txt

# Disk usage statistics
df -h

# Estimate file space usage
du -sh directory

# Copy files and directories
cp -r /source /destination

# Move files and directories
mv /source /destination

# Remove files or directories
rm -rf /directory

# Search for a string in files
grep "search_string" /path/to/files*

# Display the last part of a file
tail -f /var/log/syslog

# Display the first part of a file
head /path/to/file

