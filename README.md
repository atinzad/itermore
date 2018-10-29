# Itermore

This package contains one function, gpermutation, that works similarly to Itertools' permutations, but has the ability to permute using groups, thus the g in gpermutations. An example is shown bellow.

# Installation

     >>pip install itermore


# gpermutations(list,permutation_groups)

     from itermore import gpermutations

     gper = gpermutations(['a','b','c','d','e'],[1,0,2,1,0])

     for p in gper:

          print p

Output is 

     ('a', 'b', 'c', 'd', 'e')

     ('a', 'e', 'c', 'd', 'b')

     ('d', 'b', 'c', 'a', 'e')

     ('d', 'e', 'c', 'a', 'b')



a & d are permuted together

b & e are permuted together

c is alone
