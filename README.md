# Quintic-Equations-Approximate-Closed-Form-using-NN

One can find the exact equations of chebyshev and the LAgragian NN directly for each of the above code block , 
but for the Conventional NN architechtures used above one can use the 'Deterministic Interpretation of NN' and 'Exact Equations of the NN' papers...

Conclusion - Do the quintic equations have the algebraic equations of mapping from the coefficient space to the root space ? Exactly no , but approximately yes by NN
with errors in prediction... But more research is needed varying the architectures by Neural Architecture Search of the three methods of 1. Conventional NN , 2. Chebyshev Activation NN (Deterministic Interpretation of NN)
3. Lagrangian NN (Probabilistic Interpretation of NN) (this method is yet to be implemented for this problem)...to find the respective optimum architectures in the three methods for the given generated dataset of polynomial.

The original idea was to curvefit but was later shifted to using NN ...The original idea proof of concept is briefly discussed here - https://www.researchgate.net/publication/392595745_Closed_form_solution_of_quintic_Ie_degree_5_polynomial_equation_Proof_of_concept

One can also follow this approach to find the mapping equations of degree 2 (quadratic) , degree 3 (cubic) and degree 4 (quartic) whose equations are
already known to research the NN architechtures best suited for higher degrees ...Also one can use binary encoding of the decimal numbers and train the model on the input and output array of sizes (6, Number of Elements in the binary vector of per decimal coefficient) and (10, Number of Elements in the binary vector per real and imaginary part of root ")
