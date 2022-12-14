# RSA-Algorithm Implementation

CP 460 : Applied Cryptography Group-11

Group Members :
Yash Rojiwadia (203039360),
Jay Vora (203321900),
Owen Milne (180936570) and 
Dhruv Sagar ().


RSA Implementation in C++ :


(Key Generation, Encryption, Decryption, 2^32 base arithmetic operations)

C++ implementation of RSA algorithm for BigInteger numbers. 

In this project, a C++ implementation has been provided to perform RSA encryption and
decryption for up to 3072 bits of N value. The project also includes random public and private key
generation for RSA algorithm. In order to achieve the desired results, the design includes methods
for basic operations of N bit numbers.


How to run the code :

- The source files are in the /src folder. It contains a script file build.bash. Simply running this file
with ./build.bash command will run the code. It will generate a random set of private public key
and encrypt a random generated message and decrypt it again to show you the original number.
The executable will be generated in the /bin folder. The executable will take an input N where N
represents the number of bits of the Algorithm. i.e. 1920. If no input is given it will assume the
value of N to be 960 bits. The input value can also be changed from the script by changing the last
line of the build.bash file.
./obj <desired value of N>



References :
- RSA Algorithm Example : https://www.cs.utexas.edu/~mitra/honors/soln.html
- Donald E. Knuth The Art Of Computer Programming 4.3.1 pages 266-273
- Sanjoy Dasgupta Algorithms
- Md Jubaer Hossain Pantho : https://github.com/jubaer-pantho/RSA-Implementation-Cpp
