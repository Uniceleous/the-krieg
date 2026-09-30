# Challenge Name
vault-door-training

## Approach
(how you started, what you tried)
i first opened the given java file, then searched up the substring method for strings. then understood that the program is omitting
the starting part of the string, that is "academy{", and the curly brace at the end. 

## Solution
(the actual technique ,code, commands, screenshots)
i just copied the string given inside the checkPassword function and inserted it into academy{}

## Flag
academy{w4rm1ng_Up_w1tH_jAv4_4cfa5369b93}

## Takeaway
dont directly put passwords in the source code. encrypt it somehow.



# Challenge Name
Transformations

## Approach
(how you started, what you tried)
using cat enc i was able to see some chinese text. i looked up what the chinese characters meant in google translate but that didnt help
much. i then searched up if it was some encoded text. for the next step i was learning how to decode CJK. then used iconv after digging
for some time online.

## Solution
(the actual technique ,code, commands, screenshots)
![Solution][screenshots/s1.png]
the command converts the text from UTF 8 to UTF 16

## Flag
academy{16_bits_inst34d_of_8_790ba37e}

## Takeaway
learnt about iconv. can be helpful for other conversions as well. 