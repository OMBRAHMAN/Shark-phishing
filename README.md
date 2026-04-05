🦈 OM-SHARK: Official Installation Guide
Developed by: OM BRAHMAN
Follow these steps one by one to install and run the OM-SHARK phishing tool on your Termux or Linux terminal.
Step 1: Update & Upgrade Packages
Ensure your environment is up to date to avoid any installation errors.

pkg update && pkg upgrade -y

Step 2: Install Required Dependencies
The tool requires git to download files, php to run the server, and unzip to extract the templates.

pkg install git php unzip -y

step 3:clone the repository.

git clone https://github.com/OMBRAHMAN/Shark-phishing.git

Step 4: Navigate to the Directory
Enter the tool's folder after the download is complete.

cd Shark-phishing


Step 5: Extract the Tool Files
Extract the phishing templates and core files from the ZIP archive

unzip -o om-shark_tool.zip

(The -o flag ensures it overwrites existing files automatically without asking for permission.)

Step 6: Grant Execution Permission
Give the main script the power to run on your system.

chmod +x om-shark.sh

Step 7: Launch the Tool
Start the OM-SHARK interface.

om-shark



