In the file Solver_Explained.ipynb I have gone through explaining the #multi_step_methods known as #Adams_Bashforth and, #Adams_Moulton and also a #predictor_corrector method based on them known as #Adams_Bashforth_Moulton method. Then I have defined functions that generate the coefficients of the method of a given step number. Ultimately I've used them to solve a system Of #ODE's known as the #Kuramoto model. The Solver.ipynb file is a more streamlined and neat version of the former file. I hope it helps you:-)

I should also note that the multi-step methods need more than one initial state of the system, in order to create the needed steps (a.k.a the history) we first have to use another one-step method. Here I've used the #Runge_Kutta method of the fourth order which is also implemented explicitly. Please let me know if there is any issue with the implementation or anything wrong anywhere. Thanks.  
