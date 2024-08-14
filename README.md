
# How to Set Up Gang MLO/YMAP for FiveM (QB Core)

## Prerequisites
Before starting, ensure you have the following:
- A working FiveM server running on the QB Core framework.
- Basic knowledge of FiveM server files and configuration.
- Access to your server's file system.

## Step 1: Download and Extract the MLO Files
1. Download the MLO package provided.
2. Extract the contents of the `.zip` file to a location on your computer.

## Step 2: Upload the MLO Files to Your Server
1. Connect to your FiveM server via FTP or access the file system directly.
2. Navigate to the `resources` folder within your server directory.
3. Create a new folder inside `resources` (e.g., `gang_mlo`).
4. Upload the extracted files from your computer to this new folder.

## Step 3: Add the MLO Resource to Your Server
1. Open your server’s configuration file (`server.cfg`) using a text editor.
2. Add the following line to include the MLO resource:
   ```plaintext
   ensure gang_mlo

## Step 4: Restart the Server
Save the changes to your server.cfg.
Restart your FiveM server for the changes to take effect.

## Step 5: Verify Installation
Connect to your FiveM server using the FiveM client.
Navigate to the location where the MLO is supposed to be loaded.
Verify that the MLO is correctly installed and functioning as expected.
## Troubleshooting
If the MLO does not appear, ensure the resource is correctly named and the server.cfg file is correctly configured.
Check your server console for any errors related to the MLO resource.

## Additional Notes
Make sure to back up your server files before making any changes.
Keep your server updated with the latest QB Core version for the best compatibility.