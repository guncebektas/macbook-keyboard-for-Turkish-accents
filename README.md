# Change the order of Turkish accents in Macbook's English keyboard. 
This is the required file to change the order of accent letters for Turkish. The file in this repository is generated for English layout. You can easily edit your own keyboard layout for any other accents in any languages.

# Usage 
1. Disable System Integrity Protection. 

1.1. It might be required to use ```sudo mount -uw /``` command to unmount read-only disk. 

2. Navigate to /System/Library/Input Methods/PressAndHold.app/Contents/PlugIns/PAH_Extension.appex/Contents/Resources/ in the Finder. To go to it quickly, press ⇧⌘G and paste the string in.

3. Find your keyboard plist file. It's "Keyboard-en.plist" for English layout. It could have other names as well, depending on your keyboard language.

4. Back this file up by pressing ⌘D. Rename the copy you made to something with "backup" in its name.

5. Copy & paste the file in this repository with "Keyboard-en.plist".

6. Enable System Integrity Protection.
