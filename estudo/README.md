#### A função trace\_ray

Esta função retorna um int **it** que significa:

- it = 0; O raio NÃO deixou o grid 
- it > 0; O raio deixou o grid pelo topo
- it < 0; O raio deixou o grid pelos lados ou pela base

O tempo de trânsito total:

- nt\*dt, se it=0
- abs(it\*dt), se it != 0
