HASHCAT  
hashcat -m 0 -a 0 -o cracked.txt hashes.txt wordlist # md5  
hashcat -m 100 -a 0 -o cracked.txt hashes.txt wordlist # sha1  
hashcat -m 400 -a 0 -o cracked.txt hashes.txt wordlist # wordpress  
hashcat -m 1000 -a 0 -o cracked.txt hashes.txt wordlist # NTLM  

JOHN THE RIPPER  
john --wordlist path hashes.txt

[CRACK STATION](https://crackstation.net/)
