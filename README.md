# Face Recognition Attendance System - Installation Guide

## Prerequisites
1. Install Anaconda or Miniconda
   - Download from: [Anaconda Website](https://www.anaconda.com/download)
   - During installation, make sure to check "Add to PATH"

## Installation Steps

1. Extract all files to a simple path (e.g., C:\FaceRecognition)
   - Avoid paths with spaces or special characters

2. Open Command Prompt as Administrator
   - Right-click Start Menu
   - Select "Windows Terminal (Admin)" or "Command Prompt (Admin)"

3. Navigate to the extracted folder:
   ```
   cd /d C:\FaceRecognition
   ```

4. Run the test script:
   ```
   test_setup.bat
   ```
   - This will check if everything is ready

5. If test passes, run:
   ```
   run.bat
   ```

## Default Login
- Username: admin
- Password: admin

## Troubleshooting

If you encounter any issues:

1. Make sure Anaconda/Miniconda is installed and in PATH
   - Open Command Prompt and type: conda --version
   - Should show the version number

2. Make sure you're running as Administrator

3. Make sure your antivirus is not blocking the installation

4. Check if your webcam is properly connected

5. If you get any errors, try these steps:
   - Close all Command Prompts
   - Restart your computer
   - Run test_setup.bat again

For additional help, contact support with any error messages you see.
