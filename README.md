# Cancer_Treatment-Quantum_Solver
My work under Professor Mohammadi for accelerating cancer treatment planning using quantum computing.

Tools: Python, PhiSolve, Pandas, Matplotlib, NumPy, SciPy, JAX, Git

Background:
This work is part of a bigger research project that seeks to determine whether we can further optimize the cancer treatment planning process using quantum-inspired algorithms, namely Quantum-Inspired Hamiltonian Descent. This would help both the patient and clinician by reducing the time required to compute an Intensity-Modulated Radiation Therapy (IMRT) plan while also improving its accuracy.

My Work:
I successfully developed a program (the two notebooks) that applies PhiSolve to an MILP instance previously solved by Gurobi. The crux of the problem was to reformulate the MILP into the structure that PhiSolve's QIHD framework expects (an MIQP-style formulation with appropriate variable encodings and constraint handling).

The two notebooks were tailored to specific private data files, yet they could easily be generalized. 
