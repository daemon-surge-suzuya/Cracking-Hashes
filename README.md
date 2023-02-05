# Cracking-Hashes
This repo contains python code that can crack different types of hashes. There is also a program that can generate rainbow table from a simple wordlist.txt (e.g. rockyou.txt)

You can use hashcracking.py to crack a hash. But note that since this repo does not have a wordlist which you can use for cracking hashes you need to install your own. The one that I recommend mostly is rockyou.txt (Link - https://github.com/brannondorsey/naive-hashcat/releases/download/data/rockyou.txt).
After installing it you can use raibow_tableGenerator.py to convert this normal wordlist to rainbow table (rainbow table works faster than normal wordlist)

When you are going to use rainbow_tableGenerator.py, You need to specify the name of the hash you want to use
SUPPORTED HASHES = md5, sha256, sha384, sha224.

Then Finally, You need to specifiy the name of the wordlist you want to convert. 

IMPORTANT - Make sure that the wordlist is in the same directory as these files. 

There is another file called `hash_cracking_wordlist.py` that python program will work the same as the `hashcracking.py` but instead it does not need a rainbow table to crack. All you have to do is just have a good wordlist of password in your directory. `hash_cracking_wordlist.py` will convert passwords inside of the worlist to the required hash and then compare it to the input hash. Once, it will get a match of the hash from the wordlist. It will print it out the matched hash password.
