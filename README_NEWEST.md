# Diffie/sDes Section  
msg = [[1,1,1,0,0,1,1,0],[0,1,0,0,0,1,0,0],[1,0,0,1,0,1,0,0],[1,1,1,1,1,0,1,1]]  
A = 25 (For Diffie Hellman, A^b = shared key, use 10 LSB as your key for sDES)  
p, g = laid out in your github  
init vector = [0,0,0,0,0,0,0,0] (used for block chaining part)  

# El Gamal section
B = laid out in your github (your public key)  
 (NOTE: this makes little b, your number chosen for diffie-hellman, your private key for El Gamal to decrypt)  
p, g = laid out in your github
signature = (125, 635761)
