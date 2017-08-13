# Programmable Oblivious PRF & multi-party PSI
This is the implementation of our [CCS 2017](http://dl.acm.org/xxx)  paper: **Practical Multi-party Private Set Intersection from Symmetric-Key Techniques**[[ePrint](https://eprint.iacr.org/2017/xxx)]. 

Evaluating on a single Intel Xeon server (`2 36-cores Intel Xeon CPU E5-2699 v3 @ 2.30GHz and 256GB of RAM`) with a single thread per party, ours protocol requires only `71` seconds to securely compute the intersection of `5` parties, each has `2^20`-size sets, regardless of the bit length of the items.

## Installations
comming soon
### Required libraries
 C++ compiler with C++14 support. There are several library dependencies including [`Boost`](https://sourceforge.net/projects/boost/), [`Crypto++`](http://www.cryptopp.com/), [`Miracl`](https://github.com/miracl/MIRACL), [`Mpir`](http://mpir.org/), and [`libOTe`](https://github.com/osu-crypto/libOTe)
## Help
For any questions on building or running the library, please contact [`Ni Trieu`](nitrieu.github.io) at trieun at oregonstate dot edu

