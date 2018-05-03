
p & g -> we've used the prime and primitive root, as listed on your github

A = 1267650600228219655424634599189 (Diffie Hellman) -> Raise this to little b, convert to decimal, use 10 LSB's as key for sDES 
V = [0,0,0,0,0,0,0,1] 
msg = [[1,1,0,0,0,1,0,0],[1,1,1,1,1,0,1,0][1,0,1,0,0,1,1,1][1,0,0,1,1,0,0,1]]

For El Gamal, 
B = the Big B you've listed in your github as your Big B for Diffie Hellman (g^b mod p)
 -> !! (little b from Diffie Hellman is your private key for El Gamal to decrypt)
a = same as g, primitive root listed in your github 
p = p listed in your github
C = (1073741824, 1113267948820168910137319263601)
