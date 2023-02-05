# Cracking-Hashes
This repo contains python code that can crack different types of hashes. There is also a program that can generate rainbow table from a simple wordlist.txt (e.g. rockyou.txt)

You can use hashcracking.py to crack a hash. But note that since this repo does not have a wordlist which you can use for cracking hashes you need to install your own. The one that I recommend mostly is rockyou.txt (Link - https://github.com/brannondorsey/naive-hashcat/releases/download/data/rockyou.txt).
After installing it you can use raibow_tableGenerator.py to convert this normal wordlist to rainbow table (rainbow table works faster than normal wordlist)

When you are going to use rainbow_tableGenerator.py, You need to specify the file name of the wordlist you want to convert.
Then you have to specify the name the name of the wordlist you want to create.
IMPORTANT - Use the following names for the rainbow table that you are going to generate with different hashes 

md5 = rainbow_table_md5.txt; 
sha224 = rainbow_table_sha224.txt; 
sha256 = rainbow_table_sha256.txt; 
sha384 = rainbow_table_sha384.txt; 

Finally, You have to specify what kind of hash you want to use (md5, sha224, sha256, sha384)
