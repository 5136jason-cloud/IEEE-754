This is the final structure IEE754 for Spring lab2, the structure involves previous setup for radix-4 multiplier.
The relevant information are provided as follows: https://trekhleb.dev/blog/2021/binary-floating-point/

Thanks to @Charles-Wuu for structure setup.
  
The structure uses three parts of manipulation on the two float point numbers, the sign, the exponent and the fraction.

<img width="612" height="438" alt="Picture 1" src="https://github.com/user-attachments/assets/3f085d6c-5d25-4d49-9728-6fda296e0194" />

We first freeze the counter in PC then do XOR, addition and multiplication to the three parts respectively and check the carry bit by comparing the two highest bits of the fraction parts of the original numbers. After combining them together we have the final result.

EL.PSY.KONGROO
