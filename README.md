# Maximum-Sum-Subsequence-Parallel
Trabalho da Disciplina de Programação Paralela e Distribuída onde foi feito um estudo do problema 'Maximum Sum Subsequence' visando a implementação paralela tanto distribuída quanto compartilhada,
para observar a diferença de desempenho em cada uma delas e constatar qual implementação é mais eficiente. Para a implementação em memória compartilhada foi feito tanto um código usando pthreads quanto
um código usando openMP. Já na implementação em memória distribuída foi utilizado MPI em um código, e em outro foi implementado usando CUDA. Por fim, para chegar em melhores conclusões sobre desempenho
e eficiência, comparamos o speed up máximo de cada uma das implementações e fazemos análises comparativas em cima desses dados, chegando assim na conclusão sobre qual paralelização foi mais eficiente
para solucionar o problema.
