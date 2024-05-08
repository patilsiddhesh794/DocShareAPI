# 📄 Document Management And Sharing API

Welcome to the Document Management API, a Node.js project for managing files and folders!

## Features

### 📁 Folder Management
- **Add Folder**: Create new folders to organize your documents.
- **Delete Folder**: Remove folders along with their contents.

### 📄 File Management
- **Add File**: Upload files to your document repository.
- **Delete File**: Remove files from your repository.

### 🔗 File Sharing
- **Share Files**: Share documents with others by providing access links.

### 🔐 Authentication
- **Sign Up**: Register new users for accessing the API.
- **Login**: Authenticate users to access protected endpoints.
- **Reset Password**: Allow users to reset their passwords if forgotten.
- **Verify Email**: Verify user email addresses to activate accounts.

## Setup

### Prerequisites
 Node.js installed on your machine.

### Installation
1. Clone the repository:
-          git clone https://github.com/patilsiddhesh794/DocShareAPI.git
2. Create a `.env` file in the root directory.
 
3. Define environment variables:
 -         PORT = 3000
           DATABASE_URL = Your Database URL
           SECRET_KEY = "It's a big secret...."
           PASSWORD = YOUR_APP_PASSWORD_FOR_SENDING_EMAIL
           EMAIL = YOUR_EMAIL
       
4. Install dependencies:
   -       npm install

### Running the Server
1. Start the server: `npm start`
2. The API will be accessible at `http://localhost:3000` by default.

