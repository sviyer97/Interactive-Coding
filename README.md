# Roth's-Theorem-Notes

Sufficiently large systems must contain some objects that are structured!

This is a well-known phenomenon, first observed by Frank Ramsey almost a century ago, and several examples of this can be found in the field of [Ramsey theory](https://en.wikipedia.org/wiki/Ramsey_theory). 
Here are some very interesting ones:
1. **Any** graph with ~$n$~ vertices must contain either a clique or an independent set involving roughly ~$\log n$~ vertices.
2. If there are ~$n$~ sets of size ~$k$~ there must be a [sunflower](https://en.wikipedia.org/wiki/Sunflower_(mathematics)) with roughly ~$n^{1/k}/k$~ petals. 
A sunflower with $p$ petals is a collection of ~$p$~ sets of which any two have the same intersection.  
3. For sufficiently large ~$n$~, any coloring of the integers ~$\{1,...,n\}$~ with ~$k$~ colors must contain an arithmetic progression of length ~$t$~ -- a sequence of numbers of the form ~$a,a+d,a+2d,\ldots,a+(t-1)d$~ -- all of whose colors are the same!

Roth's theorem is a beautiful statement in mathematics that is a quantitative version of the last statement in the case of $t=3$. It says that any large enough subset of ~$\{1,\ldots,n\}$~ contains 3-term arithmetic progressions. 
A key ingredient in the proof is the use of Fourier analysis, a tool that enables one to detect periodicities/arithmetic patterns in functions.  

This writeup has a short proof of Roth's original theorem along with a subsequent improvement due to Heath Brown/Szemeredi. 
The proof of Roth's theorem is based on [this](https://www.youtube.com/watch?v=A_mL3VAHXCw) video on 3-term APs.
