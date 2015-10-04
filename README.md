USB Password Repay card is an enhancement of DIY USB password 
generator (http://codeandlife.com/2012/03/03/diy-usb-password-generator/)
by Joonas Pihlajamaa.

The subfolder contain parts of V-USB library available at 
http://www.obdev.at/avrusb/ and its contents are copyrighted by their 
respective authors. My productions in the root folder are published under 
GNU GPL v3 (see License.txt).

The enhancements comprise:
-maximum password length configured to 50 characters;
-toggling NUM LOCK adds a character and terminates generation; and
-if SCROLL LOCK is on, a newline is appended to the password message.

Defaults are for the Digispark ATTiny85 USB module, and a jumper is required 
from PB2 to PB4. (It should be possible to change the code to use PC interrupt 
and not require the jumper.)


