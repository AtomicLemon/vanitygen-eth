-----
Vanitygen ETH+! (C++ version of VanityEth+)
-----
  
**WARNING!** This program has not been thoroughly tested.  Please attempt importing an address first.  
Send a tiny amount you don't mind losing to the address.  Then perform a test spend.  
I will not be held liable for lost funds as a result of the use of this program.  
Also do not use this program for nefarious purposes!  I do not condone illegal activity.  
The chances of actually brute forcing an address is nearly impossible anyways.  
  
Be sure to report any issues or bugs and fixes, I am happy to accept pull requests!  
If you have an altcoin you would like to add please let me know.  

-----
Getting Started  
-----

I'll release binaries for Linux and windows soon :)

Fow now, here are the instructions to build on Linux:
```
git clone https://github.com/AtomicLemon/vanitygen-eth
sudo apt-get install libpcre3-dev
make
```
Assuming you already have `make` and all that jazz installed

**For generating addresses using the CPU(slower) use: vanity !**  
**For generating addresses using the GPU(faster) use: oclvanity !**  
  
**NOTES:**	All arguments are case sensitive!  
	Address prefix must be at the end of the command.  
	oclvanitygen requires OpenCL and correct drivers.  
  
Example output of above command:  
>Generating ETH Address  
>Difficulty: 65536
>Pattern: 518a                                                                  
>Address: 0x518a7f9ae5bb72e34e8bcd25f6912199169ccfa0
>Privkey: 0x17c71c86be6aef0db73b98357cba6679e598f882d46df79c1e53803a3b50e588

### Speed
On a Intel i5 CPU, I can generate around 650 Kkeys/s or 65,000 keys/second
  
-----
  
**If you found this repo useful, please consider a donation.  Thank You!**  
  
 * Donate Bitcoin: 189182eexobQMBp7uXDQWWhUC2ptT1jWfU
 * Donate ETH/Tokens: 0x2EC6f3b0B64b82Ce6b9e6a96401380C287eBd8f4
 
 Don't forget to credit the original developer! His donation addresses are on this page: https://github.com/kjx98/vanitygen-eth
