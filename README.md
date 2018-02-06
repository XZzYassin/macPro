
## Script to Setup MacBook Pro


* Author: Moh'd Alrefai
* Copyright (c) 2018 Moh'd Alrefai

This is just a simple bash shell script I use to automate installing and setup my own personal systems on `MacBook Pro`, with some options to customize the install a bit.

This hasn't been extensively tested (yet), and is tailored to the particular setup I prefer, which might not necessarily be what you prefer, so please read through the script before installing.

If you improve this script in any way, or have any suggestions, please don't hesitate to let me know. Though, I'm not trying to turn this into a universal installer.

## Technology Stack

- [Bash][0]
- [Homebrew][1] 
- [Cask][2]
- [Xcode][3]
- [RVM][4]

## Process Guide

### 1. Upgrade your mac to the latest macOS
* Here’s how to find out which OS version you’re running now:  

	I. Click Apple icon in the top left corner.  
	II. Choose About this Mac.  
	III. There you have it, in capital letters.  
	 
	![](update-os-mac.gif)
	

### 2. Clone the repository
	$ git clone git@github.com:malrefai/macPro.git <YOUR_PROJECT_DIR>
	$ cd <YOUR_PROJECT_DIR>

### 3. Make script executable
	$ chmod +x setupMacPro.sh
	
### 4. Run the script
	$ ./setupMacPro.sh

### 5. Reboot
	$ sudo shutdown -r now "Rebooting Now"
	
## Notes
The script will add some hidden files to your home directory, and will add the needed variables and PATH expansion. In additonal will create some aliases.




[0]: https://www.gnu.org/software/bash/
[1]: https://brew.sh/
[2]: https://caskroom.github.io/
[3]: https://developer.apple.com/xcode/
[4]: https://rvm.io/

