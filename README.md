# Solutions for Signal-9 CTF

## Misc 

### Sanity check 
![image](https://github.com/Artickatz/0x1.signal9.club-CTF/assets/69086568/3e354b85-f8ee-434c-9c41-570dbc947268)

### Flag Commentary 
![image](https://github.com/Artickatz/0x1.signal9.club-CTF/assets/69086568/5ce8d923-add0-48de-a453-763b3d20ae3d)

### Dashing Foward 
![image](https://github.com/Artickatz/0x1.signal9.club-CTF/assets/69086568/74df1204-7e31-481f-b5f9-7e585a191059)

### Never 

To do this challenge you need to connect to "nc challenges.signal9.club 27123" where you can do nc challenges.signal9.club 27123 > file.txt to get the flag after running a search for the flag containing the proper s9{} syntax. Giving us the flag 

### Internet Exfiltration Message Protocol 
The flag to this challenge is s9{ICMP_3xf1l3d}

## Reversing

## Cryptography 

### The Basics 0x0
We've seen hackers communicating with these strange messages, we don't know what they are, but we believe they may be using a numbering system to encode text. See if you can read the message. 01110011 00111001 01111011 01000000 00110001 00110001 01011111 00110000 01101110 00110011 00100100 01011111 01000000 01101110 01100100 01011111 01111010 00110011 01110010 00110000 00100100 01111101

![cybercherf](https://github.com/Artickatz/0x1.signal9.club-CTF/assets/69086568/a1e45340-fec7-4ce0-9431-61b8821ff75e)


This is a simple binary challenge where we can use a tool call cyber chef to solve it. So using the magic option on the binary gives us the solution whioch is s9{@11_0n3$_@nd_z3r0$}

### The Basics 0x1 
To solve this you can use cyberchef with the magic or hex decoding option

s9{h3x_w1th_th3_b3$t_d13_11k3_th3_r3$t}

### The Basics 0x2 
To solve this you can use cyberchef with the magic or base64 decoding option

s9{0n1y_th3_BASE1c$}

### The Basics 0x3
This is another base challenge so just use cyberchef with magic again

s9{W311_th@t_w@5_1355_b4$1c}

### The Basics 0x4

### Ides of March 

![ceasr](https://github.com/Artickatz/0x1.signal9.club-CTF/assets/69086568/4cc5b71a-f186-411f-896b-64e6c0d53d39)

s9{Julius_wont_be_happy_about_this}

### Quite ENIGMATIC

### RSA You Say?

### XOR Might be a chore 

### Doesn't make sense, XOR does it?

### Root of the issue 

### Custom Encryption

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

### Half-n-Half 

In an attempt to foil cryptanalysis, I have created the perfect algorithm. The algorithm flips exactly half of the bits in the plaintext at random, never flipping a bit more than once. This ensures that for any bit, there is exactly a 50-50 chance if the bit in the hash correlates to the original. To prove it's complete inability to disclose the original text, I will include 150,000 runs of this algorithm on the same plaintext, along with the generator code. Good luck decrypting what can only be described as pure random chance.


The solution flag is s9{c0ff33_cr3@m3r}

## Open Source Intelligence 

## Web

## Coding 

## Explotation 

## Log Analysis 

## Stego 




