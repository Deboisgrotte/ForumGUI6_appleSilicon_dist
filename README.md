In order to complete the install process you must use the Terminal Application:

1. Install Homebrew: https://brew.sh/

2. Install R using Homebrew:
   brew install R
   (Make sure your shell environment is configured correctly)

3. Download the Forum app, unzip it, and place it somewhere convenient (e.g., Desktop). Do NOT put it in the Applications folder.

4. Open Terminal and navigate to the folder containing Forum.app:
   cd ~/Desktop

5. Remove the quarantine flag:
   xattr -dr com.apple.quarantine Forum.app
   
6. On the first startup, the application access to its files and file location when prompted.
   
7. Done!! The app can now be launched regularly.

Note: The unquarantine command only needs to be run once per downloaded copy.
If you do not allow the application access to the file location when prompted, the app will not start.
This can be fixed by going to System settings > Privacy & Security > Files & Folders > Forum and enabling the checkbox next to the location of the application's files.
