# ProgDA_AssignmentMD
                                          #Purpose
                           
NumPy is a computing package within python that allows the use of multiple array objects, tools and functions. NumPy contains useful algebra, code and generates random numbers.

The Numpy documentation can be sourced at https://docs.scipy.org/doc/numpy-1.14.0/reference/routines.random.html


                            #Simple Random Data and Permutations

The functions included in the simple random data include rand, randn, randint,sample and choice.

Th functions included in permutations include permutations and shuffle

Simple random data and permutation function in NumPy forms a part of the random sampling function (numpy.random). 

Numpy’s random number function produces random numbers based on formations of a BitGenerator and arranges these. A generator uses these arrangements to fragment from different distributions. 



                          #Name five distributions within the numpy.random package

                   #chisquare(df[, size])	Elucidates samples from a chi-square distribution.

When random variables in a dataframe, with normal distributions, are squared and summed, a chi-square analysis is distributed. This is useful in calculating hypotheses.

               #logistic([loc, scale, size])	Elucidates samples from a logistic distribution.

The logistic distribution is useful in Extreme Value Problems, such as maximum and minimum values to real world problems. It makes the assumption that the variable is logistically and randomly distributed. 

              #geometric(p[, size])	Elucidates samples from the geometric distribution.

The geometric distribution is used in analysing problems with one of two outcomes, an example is that of rolling a die, where a six is success and all other outcomes represent failure. A geometric analysis represents the number of times a process must be activated in order for success to occur. 


               #uniform([low, high, size])	Elucidates samples from a uniform distribution.

The chosen sample are uniformly distributed over the half open interval, i.e low and high. It incorporates low values but eliminates high. Any amount that falls within the choice interval is deemed of equal liklihood to be chosen by uniform.


             #normal([loc, scale, size])	Elucidates random samples from a normal (Gaussian) distribution.

The normal distribution represents the frequently presented distribution of samples each with a unique distribution occuring randomly, often in nature. 


                       #The use of seeds in generating pseudorandom numbers


The random.seed function in python returns the hidden generator of random numbers utilsed by python in the random component.

A pseudorandom number is a design for producing a sequence of numbers that closely resemble random numbers. The process is not authentically random, as it is derived from an original value, known as the seed, which can involve random values. 



References

https://numpy.org/

https://docs.scipy.org/doc/numpy-1.14.0/reference/routines.random.html

https://realpython.com/python-random/

https://docs.scipy.org/doc/numpy-1.14.1/reference/routines.random.html

https://docs.scipy.org/doc/numpy-1.16.1/reference/generated/numpy.random.logistic.html

https://en.wikipedia.org/wiki/Pseudorandom_number_generator

