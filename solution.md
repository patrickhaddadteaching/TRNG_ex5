* How the jitter variance and the number of xored oscillators impact the throughput of a MO-TRNG successfully passing the 5 black box tests included in the AIS31 test suite (four of which are also included in the FIPS 140-1) ?
	- For a given number of xored oscillators, lower the jitter variance is, less black box tests succeed 
	- For a given jitter variance, lower the number of xored oscillators is,, less black box tests succeed 

What can be drawn from the black box tests success when $\frac{σ_{tot}}{T1}=0 ?
  - The black box tests can be cheated by a deterministic stream
