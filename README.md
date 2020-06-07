Mounting of Google Drive as the file system on our computer using Google API application.It provides features to use google products in our application, rather than creating newones.
### Steps:
 -  **Authentication**: Authentication is done using Oauth2.It returns a token that is used to access google drive thereby providing security.
 - **Mountpoint**: Creating a Mountpoint on the local system using fuse filesystem.Mountpoint creates a image of the google drive on the system. 
 - **operations**: operations like viewing of files currently present in the google drive,downloading and uploading of files/folders,creating new directory,renaming of files/folders,deletion of existing files/folders from the drive etc are all performed using the system's terminal and the respective changes are reflected on google drive.
 
 ### Technologies invloved:
 - python3
 - ubuntu

