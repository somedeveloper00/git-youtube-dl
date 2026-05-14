# Experimental Downloader 
**A collection of GitHub Actions workflows for downloading videos, websites, direct files, torrents, and custom Bash outputs directly inside your own fork.**

## 🚀 Getting Started
1. Fork this repository
2. Open the Actions tab in your fork
3. Select the workflow you want to use
4. Fill in the required inputs
5. Run the workflow
6. Wait for completion
7. Open the corresponding branch to access download links
___

## Available Workflows

### 🎥 Video (YouTube, X, etc.)
1. Fork the main branch
2. Run the "Video Downloader" Workflow in the Actions tab (ensure link is filled)
3. Await completion (Some videos will fail)
4. Switch to the `videos` branch
5. View download links

### 🌐 Website (ファミ通, X, etc.)
1. Fork the main branch
2. Run the "Website Downloader" Workflow in the Actions tab (ensure link is filled and name is unique)
3. Await completion
4. Switch to `web` branch
5. View download links

### 🔗 Direct Link Download (Wget)
1. Fork the main branch
2. Run the "Wget Downloader" Workflow in the Actions tab (ensure link is filled)
3. Await completion
4. Switch to `wget` branch
5. View download links

### 🧲 Magnet Download (aria2)
1. Fork the main branch
2. Run the "Magnet Downloader" workflow in the Actions tab (ensure magnet link is filled and folder name is unique)
3. Await completion
4. Switch to `magnet` branch
5. View download links

### 🐧 Bash Executor (downloads . directory)
1. Fork the main branch
2. Run the "Bash Executor" workflow in the Actions tab (ensure Bash command field is filled and output name is unique)
3. Await completion
4. Switch to `bash` branch
5. View download links

#### 📽️ How-to's Screen-record 
This video showcases a simple workflow: https://abrehamrahi.ir/o/public/fAYx7OTW/

#### 🎤 How do I view multi-file downloads?
Download all the parts, then unzip the file ending with `.zip`

#### 🎤 How do I view downloaded Websites?
Unzip the downloaded file and open the `archive` folder inside it. You can either
- (For experts) Open the index.html file on your browser
- (For non-experts) View the generated pdf file
- (For non-experts) View the generated screenshot

#### 🎤 How do I delete the downloaded files from the repository?
Click on this button in your repo's main page to access the list of branches:  
[Main repo page circling the branches page button](https://abrehamrahi.ir/o/public/8tQTYpkc/).  
Then delete the branches you no longer need.

#### 🎤 How do I use multiple workflows simultaneously?
For simultaneous workflows of the same type (e.g. if both are Video), you can use the Branch Name option to use two different branches.   
Simultaneous workflows on the same branch will result in falure of all but one workflows.

#### 🎤 There's a bug, what should I do?
This method is very much experimental and doesn't work for 100% of the cases. Create an Issue if you can.

## ⚠️ Legal Disclaimer
**This tool is for educational purposes and personal archiving only.** 
By using these workflows, you agree to the following:
*   **Respect Copyright:** You must not download, distribute, or archive copyrighted material without the explicit permission of the copyright owner.
*   **Terms of Service:** You are solely responsible for ensuring that your use of this tool does not violate the Terms of Service of the websites you are accessing (e.g., YouTube, X, Famitsu).
*   **Liability:** The creator(s) of this repository are not responsible for any misuse, copyright infringement, or account bans that may occur from using these workflows. 
*   **Fair Use:** Please ensure your archiving aligns with Fair Use laws in your jurisdiction.
