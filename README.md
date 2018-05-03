# CryptoProject7
p & g -> we've used the prime and primitive root, as listed on your github

A = 1267650600228219655424634599189 (Diffie Hellman)
-> Raise this to little b, convert to decimal, use 10 LSB's as key for sDES
V = [0,0,0,0,0,0,0,1]
msg = [[1,1,0,0,0,1,0,0],[1,1,1,1,1,0,1,0][1,0,1,0,0,1,1,1][1,0,0,1,1,0,0,1]]

#not yet done but we are working on this now
For El Gamal, 
  A = private key = the same key exchanged via Diffie Hellman (A^b, the whole number, not just the last 10 bits)
  a = same as g, primitive root listed in your github
  p = p listed in your github
  B = a^A
