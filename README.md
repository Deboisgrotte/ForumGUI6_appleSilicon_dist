1. Install Homebrew: https://brew.sh/

2. Install R using Homebrew:
   brew install R
   (Make sure your shell environment is configured correctly)

3. Download the Forum app, unzip it, and place it somewhere convenient (e.g., Desktop). Do NOT put it in the Applications folder.

4. Open Terminal and navigate to the folder containing Forum.app:
   cd ~/Desktop

5. Remove the quarantine flag:
   xattr -dr com.apple.quarantine Forum.app

6. Launch the app:
   open Forum.app

Note: The unquarantine command only needs to be run once per downloaded copy.
