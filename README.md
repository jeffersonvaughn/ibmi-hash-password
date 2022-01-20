# ibmi-hash-password
Using python on ibm i, accepts password/pass phrase and returns hash value

Hashitr.sqlrpgle - program that accepts a char(32) password/pass phrase and returns a char(128) hash value. 

Hashit.py - simple python script utilizing sha256


SHA256 with pass phrases is “better” than scrypt.

Why “better”?

Scrypt is system taxing due to its characteristics of a heavy algorithm with purpose of slowing down the brute force attempts… 
A company with a large user base (using scrypt) could actually tax the system (to a notable amount) just by signing on using something as heavy duty as scrypt.  
In our IBM I world, those larger user bases are not uncommon.


