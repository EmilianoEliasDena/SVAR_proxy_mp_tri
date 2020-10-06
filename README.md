# proxy_mp_tri
 Code for proxy SVAR simu paper

## notes: 
1. For Monte Carlo simulations: A complete simulation with full sample size and iteration steps could take a while. Please use "Showcase.R" to run a small-scale Monte Carlo experiment. For replication of the results, please use "Replica.R" to extract the files from the folder Replica. These results are generated on the StatOek3 Server.
2. For application: In order to increase the readability of the code, I did not put “set.seed” all over the place. For 100%-replication of the results, please use “set.seed(1234)”.
3. All involved functions are collected in the local package “Functions”. 
