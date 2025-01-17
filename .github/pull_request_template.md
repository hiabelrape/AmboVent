<!-- Note that this is a markdown comment. It won't show up in your text. You don't have to delete
these. -->
## Description:
<!-- What problems does this solve? How? Use as many lines as you need to. -->


## Checklist:
<!-- You may delete this whole section if your PR is not modifying any software/code. -->
<!-- Add an X inside the square brackets below when you've completed each item. This PR cannot
merge until you have completed all items. -->

- [ ] I have run the code formatter with `./run_clang-format.sh` (see main 
[README.md](https://github.com/AmboVent-1690-108/AmboVent#software) for details on how).
- [ ] I have built the code in the Arduino IDE (or with the command-line tool) and pasted the 
  **last 2 lines** of the build output below, so others can see how my changes affect the _size_ of 
  the built binary application. 
    - [ ] I have also updated all information in the header above the build output below to describe 
      the build conditions.
- [ ] If I have touched *any* lines of code in the software, other than comments, I have incremented
  the version number string at the top of "ventilation_machine.ino" and updated the Software 
  Changelog in the main AmboVent readme.

**Arduino IDE build output:**  

<!-- Description of the output below:
YYYY.MM.DD-HH:MMhrs is the date and time you ran the build command; ex: 2020.04.20-00:49hrs means 20
April 2020 at 00:49 hrs (12:49AM--just after midnight). Also be sure to include at least the first 7
chars of your git hash for the commit you had checked out when you performed the build. Also 
specify your Arduino IDE version number and board. The board when building should be the Arduino 
Nano unless you know differently. -->

*Date and time I performed the build:* YYYY.MM.DD-HH:MMhrs  
*Git hash of the commit I performed the build on:* <7+ char git hash>  
*IDE Version:* ?.?.??  
*Board I had selected during the build:* Arduino Nano  
*Pull Request this build is for:*  #???  

*Last 2 lines of the build output, to see how the binary size changed:*  

Sketch uses 99999 bytes (99%) of program storage space. Maximum is 32256 bytes.
Global variables use 9999 bytes (99%) of dynamic memory, leaving 9999 bytes for local variables. Maximum is 2048 bytes.

<!-- Example:

*Date and time I performed the build:* 2020.04.20-00:49hrs  
*Git hash of the commit I performed the build on:* 493985f  
*IDE Version:* 1.8.12  
*Board I had selected during the build:* Arduino Nano  
*Pull Request this build is for:* #46  

*Last 2 lines of the build output, to see how the binary size changed:*  

Sketch uses 18176 bytes (56%) of program storage space. Maximum is 32256 bytes.
Global variables use 1046 bytes (51%) of dynamic memory, leaving 1002 bytes for local variables. Maximum is 2048 bytes.

-->

