AsiaCoin SCAM - Forensics

This is the recovered code from original Asiacoin that was deleted from github

I added 2 things:
  - 1) identified where the code that allowed the premine to be invisible.  
    - search for //SCAM  
    - https://github.com/micryon/AsiaCoinFix/search?q=SCAM&ref=cmdform
  - 2) Commented out the RPC code that hid the real max coins.
    - https://github.com/micryon/AsiaCoinFix/blob/9b676b63b798038cca4b15887136774f2e6eed89/src/bitcoinrpc.cpp#L331
    
For learning purposes .. for now

  
    
