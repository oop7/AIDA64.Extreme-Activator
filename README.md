# **AIDA64 Extreme Activation Script**

This script simplifies the process of activating AIDA64 Extreme by automating the activation process with a single click. It includes features for copying necessary files and handling administrative privileges.

## 💪 Features

- Base64 Decoding: Decodes Base64-encoded files required for activation.
- Administrative Privileges: Requests elevation to run the script with administrative privileges.
- File Operations: Copies necessary files to the AIDA64 Extreme installation directory.
- Interactive: Provides a simple menu for user interaction and options.

## 🛠️ Installation

### **Method 1**
1. Download: Obtain the latest version of the tool from the [releases page](https://github.com/oop7/AIDA64.Extreme-Activator/releases).
2. Extract: Unzip the downloaded file to a directory of your choice.

### **Method 2**
1. **Open PowerShell**:
   - Right-click the Start menu and select **Windows PowerShell** or **Windows Terminal**.
   - If prompted by User Account Control (UAC), click **Yes** to allow PowerShell to run with administrative privileges.

2. Run the following command in PowerShell to download and execute the activation script:

   ```powershell
   irm https://github.com/oop7/AIDA64.Extreme-Activator/releases/download/v1.2/v1.2.zip -OutFile v1.2.zip; Expand-Archive v1.2.zip -DestinationPath . -Force; cmd.exe /c .\v1.2\script.bat
   ```

## 💻 Usage

### 1. Run the Script:
- Double-click on `script.bat` to run. The script will automatically request administrative privileges if needed, so you no longer need to manually select "Run as Administrator."
- If prompted by User Account Control (UAC), click Yes to grant the necessary permissions.
- Once elevated, the script will continue running with the appropriate permissions for file operations.

### 2. Follow the On-Screen Instructions:
- Choose an option from the menu:
- `1` to activate AIDA64 Extreme.
- `2` to exit.
- If you select 1, the script will decode the Base64 encoded files, copy them to the appropriate directory, and provide feedback on the operation status.

## ✅ Troubleshooting

- **Administrative Privileges**: If the script does not prompt for administrative rights, ensure you are running it with the required permissions by right-clicking and selecting Run as Administrator.
- **File Paths**: Verify that the encoded.txt and ASCII_art.txt files are correctly placed in the src directory.
- **Warning**: The default installation path for the software is:
``C:\Program Files (x86)\FinalWire\AIDA64 Extreme``
If the software is not installed in this directory, please ensure the path is correct before continuing.

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## ℹ️ Acknowledgments

- Special thanks to CHiLi, which was instrumental in this script's functionality.

## ❓ Contact

For questions or support, please open an issue on the GitHub repository.

