# NetscreenHash
Small Python 3 script with two function for dealing with Juniper SSG Netscreen hashes.

`makepass(user, password)` allows the user to generate a Juniper Netscreen SSG style hash.  

`reversetomd5(knownhash)` reverses the Netscreen hash to a standard salted MD5 hash.

`reversetomd5(knownhash)` has been implemented in Hashcat as mode 22 for the purposes of needing to crack a hash.  

Thanks to [phillips321](https://www.phillips321.co.uk/2014/01/10/cracking-a-juniper-netscreen-screenos-password-hash/) for figuring this out.  
