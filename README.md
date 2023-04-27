
# Exploration of integrals of powers of functions that have a simple pole

## Authors
1) Rudolph Dwars
2) Kalpesh Muchhal

## Links to papers
Currently, we have explored integrals of powers of two functions :
1) reciprocal of the log function ([direct link to paper](https://github.com/km-git-acc/power-integrals/blob/main/log_power_integrals/An%20exploration%20of%20integrals%20of%20powers%20of%20the%20reciprocal%20of%20the%20log%20V1d1.pdf))
2) zeta function ([direct link to paper](https://github.com/km-git-acc/power-integrals/blob/main/zeta_power_integrals/Roots%20of%20integrals%20of%20powers%20of%20the%20zeta%20function%20V1d1.pdf))

## Summary of key results
### 1) Discovery of new constants that can be interpreted as generalizations of the Ramanujan-Soldner constant (RS=1.451369..)
     | exponent q | root of L(q,x)=0 | root of Zi(q,x)=0 | 
     |------------|------------------| ------------------|
     | 0.51       | 1.000669 | 1.000694 |
     | 0.55       | 1.012343 | 1.012832 |
     | 0.6        | 1.039038 | 1.040602 |
     | 0.8        | 1.211222 | 1.217270 |
     | 1.0        | 1.451369 | 1.447265 |
     | 1.5        | 2.349101 | 2.052350 |
     | 2.0        | 3.846468 | 2.476428 |
     | 2.5        | 6.319568 | 2.746947 |
     | 4.5        | 46.451592| 3.579452 |
   
   In the L case, we also observe root_(q+1)/root_q -> exp(1) = 2.71828.. as q gets larger 
   In the Zi case, we observe root_(q+1)/root_q -> 1 as q gets larger 
   
### 2) Analytical continuation and roots
  We analytically continue L(q,z) and Zi(q,z) to the complex plzne z and again observe interesting properties. For eg. real(L(q,z)) shows q negative roots for q integer, apart from the one root on the positive x axis that was shown earlier, hence a total of q+1 roots.
  
  Similarly we explore the roots of symmetric sums like M(n,z) = L(n,z) + L(n,1-z) or M(n,z) = Zi(n,z) + Zi(n,1-z), and numerically it seems all the roots of such M(n,z) are on the critical line.
  
