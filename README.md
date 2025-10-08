# n8n automation to control google drive using whatsapp

### whatsaap commands
- LIST /FolderName: Get all files in a specific folder.
- /LIST FILES: Get a list of all files in the root.
- /LIST FOLDERS: Get a list of all folders.
- DELETE /FolderName/file.pdf: Delete a specific file.
- MOVE /SourceFolderName/file.pdf /DestinationFolderName: Move a file between folders.
- SUMMARY /FolderName: AI-Powered! Summarizes the contents of files within that folder using the Gemini API—perfect for quickly grasping what's inside a document heavy folder.
- RENAME /file/NewFileName.pdf: Rename a file.
- UPLOAD /FolderName/filename: Upload a file to a specific folder.

## 🛠️ Tech Stack
- n8n for the core workflow automation.
- OAuth 2.0 for secure Google Drive authentication.
- Google Gemini API for generating smart summaries.

## 🛠️ Getting Started

Follow these steps to run this automation locally on your device:

### 📦 Prerequisites
- n8n locally installed or in cloud
- create OAuth 2.0 Client ID and secret and enable google drive api
- gemini api key

## 🚀 Run the workflow

### 1. Clone the repository and download the josn file
```bash
git clone https://github.com/khan1104/n8n.git
```

### 2. open n8n and import the json file 

### 3. copy and set webhook url in twilio console 
<div align="center">
<img width="220" height="450" alt="webhook" src="https://github.com/user-attachments/assets/8f050903-f692-4711-9726-6d7d45e94c18"/>
<img width="400" height="500" alt="twilio" src="https://github.com/user-attachments/assets/19854b5f-b3ba-4b0b-bc17-e05182eb0d6a"/>
</div>

### 4. create credential in google drive node and add client ID and client secret and connect with google 
### 5. add gemini api key in google gemini chat model

### now click on execute workflow and open the whatsaap and enter the commands







