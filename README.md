 # A class for exponential random variables 

>- 1 - Define a class exponential **Exponential** with **\_\_init\_\_(self,λ)** method where **λ** is the parameter of the distribution. Supply a method **pdf** that returns the pdf function $p(x)=\lambda e^{—\lambda x}$.
>- 2 - Explain how the method of inverse distribution function presented during the lesson can be used to simulate realizations of random variables with exponential distribution. Write a method **rvs(n)** that implements this technique and returns a sample of size **n**. 
>- 3 - Define a method **hist(x)** that plots the histogram of sample list (or array) **x** together with the pdf of the exponential distribution with parameter $\lambda =1/sum({\bf x})$. Explain this choice of $\lambda$ (hint: consider the mean of an exponential distribution). 
>- 4 - Test these definitions on an example.