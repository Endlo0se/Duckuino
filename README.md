# Duckuino for ESPloit  
  
Dckuino.js was originally written by Plazmaz and Nurrl to convert Ducky Script payloads into Arduino sketches which in turn would be uploaded and ran on an Arduino board.  
  
The version in this repository has been modified by Corey Harding to convert Ducky Script payloads for devices which are running the ESPloit software, such as the Cactus WHID.  
  
Simply copy/paste or write your Ducky Script into the text area on the left, click Compile, and then copy/paste or download the output from the text area on the right to be used with ESPloit.  

A live version is available at: https://exploitagency.github.io/Duckuino/index.html  
  
# Pseudo Ducky Script commands exclusively for Duckuino ESPloit  
  
**PINBRUTE [#_OF_DIGITS] [#_OF_ATTEMPTS_BEFORE_A_DELAY] [DELAY_IN_MILLISECONDS]**  
Arguments [#_OF_ATTEMPTS_BEFORE_A_DELAY] & [DELAY_IN_MILLISECONDS] are optional.  
Example code: 
```
DEFAULTDELAY 500
PINBRUTE 4 5 30000
```
-Sets the default delay to 500ms between attempting each pin.  
-Tries all 4 digit pins from 0000-9999.  
-After 5 pin attempts there is a 30 second delay(30,000 milliseconds).  
  
# Original Authors  
  - [Plazmaz](https://github.com/Plazmaz)  
  - [Nurrl](https://github.com/Nurrl)  

