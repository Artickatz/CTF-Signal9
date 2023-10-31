# Solutions for Signal-9 CTF

## Misc 

## Reversing

## Cryptography 

### Russian Crib 

![solve](https://github.com/Artickatz/0x1.signal9.club-CTF/assets/69086568/9ee6e4bd-af8e-4095-abb0-aeeee076d395)

Our spies have uncovered 3 distinct messages from Russian Cyber Operations. We believe these messages are encrypted with a simple XOR operation, and our previous efforts have shown that this threat actor prefaces each message with the plaintext "Товарищи, " translating to "Comrade, ". Each of these raw messages have been encoded in Base64 before being given to you here, so you'll have to undo that before you crack the encryption. We believe this APT is preparing a major attack, and retrieving the password to their operational C2 server could save millions of dollars, or even human lives, good luck. Please submit in the format s9{PASSWORD}

Also attached are three files 

**Secret Message One**
ASMBPQANAAUAAAACATcABPyfATsBPgEwATcAAAEx8VNsbluVAT0ACgADAAkBPgE5ATLxU1NlZVBhUFGt8G9PZWFRUGpubmttXJ8BNvFebFJgZFlQZFFtUlOfATQBNQE6AAwACQE/AA/xX1JSb2RRUGFRY1Nrb2VlbFBoa1+eAATwb2tcb15sU1JkUVBvUWpSX5/9lRMrAAIACQAOAAoADQAMAT8BPgE5jlFvUlJvamRRUVtrUm9bbGngAA4BOwE4ATQAAo6w47ASBA==

**Secret Message Two**
ASoABgE2ATABPgAKATkABfyYATrxWVBoYVRloAE/AAwADgAMATEADQAKATT9pAAHATwADPBhXWxSaG6VATUABgE2AT4AC/BjWGBobFRpUGVvWGJoYVRsUGhuZZIBMQAMAAAADgE28GlQpAACAAAACQAKAT7waGJkUVhgaGJUYa7wbnVibmFSbF+YAAsBNQAA8VVQUGxubmJjYGttaJgACgE9ATgBMQAFAAwAAgEyAAUBOgE58VhtaGFVWVBlngAFAAABNQAAATEACAAGATYBMAADAA8ADgAI8GlRZW9YbmhgVVhQZW5tYmhgZZHwaG5lbFhomAE5ATXwb1FibGBubWNoa2VpqAANATcBPvBvUGJgYVFsWGhoZFVZUGhvVGNQYG9SY1ye8G1NaGBkWVhomAAMAT8ABgAMAA0BNvBoY2VvWGJob1VRUV9vUp7wYVdsUmhulQE3AA0ABAE1AAoAAgE+AT/waVBlYVlRaVlUaVFUb1BibmBibWppU5UBNQANAT4BPgE8AAwBMAE2AATwZFBZUmlSVGVQZW5tY1JgYG1slPBlblhuaVxVU1BubmxjU5ABMvBobWVkqAE5AToBPAADAAcAAgANATYBNAAE/JgAAwACAADwYm1gYGxYaGiVATYABwExAAAADgE0AAgABfBob2VvWGtobFRvUVFvUmNcYV6dAAkAAAE/AAYBOwEwAT8ADwE7/p0AIgAOAAYBP/FUZlBgbmJjUmFQbWBpWGVsWGVoYlRvoAAKAA8BP/CQ8GlRZWpYbmhjVG+gEhUBMwEzAAIADQE1ATIABgE4AT8BMgE8ATIACAE4Eg7/

**Secret Message Three**
ASMBPQANAAUAAAACATcABPyfATsBPgEwATcAAAEx8VNsbluVAT0ACgADAAkBPgE5ATLxU1NlZVBhUFGt8G9PZWFRUGpubmttXJ8BNvFebFJgZFlQZFFtUlOfATQBNQE6AAwACQE/AA/xX1JSb2RRUGFRY1Nrb2VlbFBoa1+eAATwb2tcb15sU1JkUVBvUWpSX5/9lRMrAAIACQAOAAoADQAMAT8BPgE5jlFvUlJvamRRUVtrUm9bbGngAA4BOwE4ATQAAo6w47ASBA==

Each message contains a part of the message and when combined you can get the flag 

The attack you will be running on this is called a known plaintext attack where the known plaintext is "comerade" 

Translated in english you will get Known Plain Text 123 

Which when converted back to english gives you the flag s9{известный_открытый_текст_123}

## Open Source Intelligence 

## Web

## Coding 

## Explotation 

## Log Analysis 

## Stego 




