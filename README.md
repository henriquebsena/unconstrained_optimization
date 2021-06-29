# ESTUDO SOBRE OTIMIZAÇÃO IRRESTRITA 

**BIBLIOGRAFIA:**
    
    [1] S. K. Mishra, B. Ram. 2019. Introduction to Unconstrained Optimization with R. Springer. 


**OBJETIVO GERAL:** Estudar livro texto [1] e apresentar uma versão Python dos algoritmos e códigos contidos nos capítulos, assim como adicionar algumas informações extras e criar um material (simples) para complementar o estudo e agilizar alguma possível necessidade.


**FORMA DE CONSTRUÇÃO DE MATERIAL:**

    I) Leitura completa do capítulo;  
    II) Pesquisa por algum material complementar;
    III) Teste dos códigos e algoritmos do livro na versão R;
    IV) Migração dos códigos R em (III) para a versão Python no Jupyter Notebook;
    V) Construção do arquivo final no Jupyter Notebook;
    VI) Upload no repositório.


**AVISO:** A editora Springer tem direitos sobre o capital intelectual dos códigos originais e trechos do livro texto que são utilizados aqui. Desta forma, este material é somente para estudo e melhoria de conhecimento, sendo ilegal a venda do mesmo ou a obtenção de qualquer lucro. Além disso, deve-se ter em mente de que este material é construído para melhorar meu conhecimento na área e por isso não deve-se assumir que os códigos vistos aqui são totalmente precisos ou corretos.

**LIVRO TEXTO - CONTEÚDO:**

    1 Introduction ........................................... 1
        1.1 Historical Note on Unconstrained Optimization ............. 1
        1.2 History of ....................................... 4
        1.3 History of Algorithm ................................ 5
        1.4 Motivation to Use in Optimization ..................... 6
    
    2 Mathematical Foundations ................................. 9
        2.1 Vectors and Matrices ................................. 9
        2.2 Eigenvalues and Eigenvectors ........................... 15
        2.3 Neighborhoods ..................................... 20
        2.4 Algorithm ......................................... 23
        2.5 Taylor’s Theorem ................................... 26
        2.6 Quadratic Functions ................................. 27
        2.7 Exercises ......................................... 31
    
    3 Basics of R ............................................. 35
        3.1 Introduction ....................................... 35
        3.2 Basics of Programming ............................. 36
        3.3 Decisi on-Making and Loop Statements ................... 45
        3.4 Graphics ......................................... 51
        3.5 Exercises ......................................... 54
    
    4 First-Order and Second-Order Necessary Conditions ............. 57
        4.1 Introduction ....................................... 57
        4.2 Directional Derivative ................................ 64
        4.3 First-Order Necessary Condition ........................ 67
        4.4 Second-Order Necessary Condition...................... 73
        4.5 Second-Order Sufficient Condition for Interior Case .......... 78
        4.6 Exercises ......................................... 82
    
    5 One-Dimensional Optimization Methods ...................... 85
        5.1 Introduction ....................................... 85
        5.2 Interval Halving Search Method ........................ 86
        5.3 Fibonacci Search Method ............................. 91
        5.4 Golden Section Search Method ......................... 101
        5.5 Quadratic Interpolation Search Method ................... 107
        5.6 Bisection Method ................................... 112
        5.7 Newton–Raphson Method ............................. 116
        5.8 Secant Method ..................................... 119
        5.9 Case Study: Producing Micro Electronics for Lithography ..... 122
        5.10 Exercises ......................................... 129
    
    6 Steepest Descent Method.................................. 131
        6.1 Introduction ....................................... 131
        6.2 Basics of Steepest Descent Method...................... 132
        6.3 Steepest Descent Method .............................. 136
        6.4 Convergence Analysis of Steepest Descent Algorithm ......... 146
        6.5 Case Study: Portfolio Selection Problem .................. 160
        6.6 Exercises ......................................... 171

    7 Newton’s Method ....................................... 175
        7.1 Introduction ....................................... 175
        7.2 Newton’s Method for Multiple Unknowns ................. 176
        7.3 Convergence Analysis of Newton’s Method ................ 183
        7.4 Modified Newton’s Method ............................ 188
        7.5 Levenberg–Marquardt Method .......................... 194
        7.6 Case Study: Optimal Design of a Pi-Electric Circuit ..... 203
        7.7 Exercises ......................................... 208
    
    8 Conjugate Gradient Methods .............................. 211
        8.1 Introduction ....................................... 211
        8.2 Basics of Conjugate Direction .......................... 211
        8.3 Convergence Analysis of Conjugate Direction Method ........ 217
        8.4 Method of Conjugate Gradient ......................... 222
        8.5 Method of Conjugate Gradient for General Functions ......... 231
        8.6 Case Study: Solving System of Linear Equations in Electrical Engineering ...... 239
        8.7 Exercises ......................................... 242

    9 Quasi-Newton Methods ................................... 245
        9.1 Introduction ....................................... 245
        9.2 Basics of Quasi-Newton Methods ....................... 245
        9.3 Approximating the Invers e Hessian...................... 247
        9.4 The Rank One Correction Formula ...................... 250
        9.5 Convergence Analysis of Rank One Correction Formula ....... 258
        9.6 Davidon Fletcher Powell Method........................ 260
        9.7 Convergence Analysis of DFP Method ................... 268
        9.8 Broyden–Fletcher–Goldfarb–Shanno Method ............... 273
        9.9 Case Study: Heat Conduction Problem .................... 284
        9.10 Exercises ......................................... 287
