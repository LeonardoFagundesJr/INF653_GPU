# Logos de Colaboradores do Trabalho


# Atividades nos Colabs
## [1. Hello World, Blocos e Threads](https://colab.research.google.com/drive/1INsl6NddQSyR-O8I2ivKWB3bmP1T20NN?usp=sharing)
1. Lucas - Tabela Placas, Codigo Multiplos Threads e Blocos (não tem limite blocos, ao usar um int para random limita maximo Blk*thr) - Feito.

## [2.Alocacao Memoria e Soma de Vetores](https://colab.research.google.com/drive/1R_DOeVF2_N_Fjrry-cK7WVifVw3a37xE?usp=sharing#scrollTo=bhp-cmJnyI1c)

1. [Leonardo](https://colab.research.google.com/drive/1X0mcyFsF52y5C2LbGmlTAsNeNXY6Vv8l?usp=sharing) transferencia GPU-CPU tabela - Feito. 
1. Ruan - Tempo de execução tabela - Soma de Vetores para GPUs e tamanhos

## [3. Intensidade Aritmetica (Polinomios)](https://colab.research.google.com/drive/1w_G16IwUZVhMzvU-uWpjGx965gkzByoO?usp=sharing) [Video](https://youtu.be/0Upfm1wktRE) - [Ler seçao 1.1 do capitulo do Mini-Curso do WSCAD 2019](https://sol.sbc.org.br/livros/index.php/sbc/catalog/view/46/200/414-2)

1. Ruan - Exercicio 1,2,
1. [Leonardo](https://colab.research.google.com/drive/15bCe-5pYbBJzqiLDFHd0oWQ5Tz_cDKVj?usp=sharing) - Exercicio 4

Caso não seja uma T4, aproveitar para fazer o exercicio 3 e 5.

## [4. Mais trabalho por Thread](https://colab.research.google.com/drive/1CgR9VjmzA_9RLtTaRk1NhHlkJatqTl_f?usp=sharing)

1. [Leonardo](https://colab.research.google.com/drive/1KpugwV1AW0cSCHAQU5hS3JkFcF-XHaoz?usp=sharing) - Exercicio 1 T3 e T4
2. Ruan -  Exercicio 1 T5 e T6
3. Lucas - Exercicio 1 a parte do FOR.

[Ruan e Leonardo _ Video para Mais trabalho, latencia e Multiplicacao Matrizes](https://www.youtube.com/playlist?list=PLcvOyD_LMr6l2OmlneylIx8OR9MbpQ-jM)

### latencia
1. [Leonardo](https://colab.research.google.com/drive/1KpugwV1AW0cSCHAQU5hS3JkFcF-XHaoz?usp=sharing) - Exercicio 3 - L1 e L2 para T1 e T2 
2. Ruan - Exercicio 3 - L3 e L4 para T1 e T2 
3. L3 e L4 para T3 e T4 Lucas
4. L5 e T2,T4 e T6 Westerley

## [5. Multiplicação de Matrizes](https://colab.research.google.com/drive/11PgsBNA-5Q8A3Kuy6QQINzoiKJKrYX_y?usp=sharing)

1. Ruan - versão CPU com ladrilhos, exercicio 1. Na GPU memcpy Exercicio 2. [memcpy Volvok](https://bitbucket.org/rvuduc/volkov-gtc10/src/master/memcpy_k.cu)
2. [Leonardo](https://colab.research.google.com/drive/1w5VcAw6oqMQzFYWl6TxyOIVbb8Wa3DnW?usp=sharing) - exercicio 3 com 2 threads (compilar com nvcc -arch=sm_XX -Xptxas -v, para ver qtos registros para 1 ponto e 2 pontos por thread)
3. Lucas - exercicio 3 com 4 threads
4. Westerley - exercicio 3 com 8 threads

## [6. Capitulo 2 - Cuda C Professional Programming - Soma de Matrizes](https://colab.research.google.com/drive/12gSlJmMHrUOQyZDg8Io9gptJ2_dckSNp?usp=sharing#scrollTo=esfCfLsZ5QRV)

1. [Leonardo](https://colab.research.google.com/drive/1QG7HVyKydWZDR4nvRwvAWcFSycsX3IIt?usp=sharing) - Exercicio 1 (cap2) [video](https://www.youtube.com/watch?v=uzE6ztaVjTw&list=PLcvOyD_LMr6lZ35IJrqjeF1bUex6Jd7Rh&index=1)

## [7. Capitulo 3 - Cuda C Professional Programming - Redução](https://colab.research.google.com/drive/12gSlJmMHrUOQyZDg8Io9gptJ2_dckSNp?usp=sharing#scrollTo=esfCfLsZ5QRV)

1. [Leonardo](https://colab.research.google.com/drive/1DDWJC__fm_wq9e06f2Lt-AWLDg6-h8yt?usp=sharing) - Exercicio 2 (cap3) [video](https://www.youtube.com/watch?v=OuMY259rXW4&list=PLcvOyD_LMr6lZ35IJrqjeF1bUex6Jd7Rh&index=3)

## 8. Explorando exemplos do Github da Nvidia

@@ -79,7 +79,7 @@ Sugestão é baixar os codigos com git para o colab. Navegar na pasta, compilar

### Tarefas

* [Leonardo](https://colab.research.google.com/drive/12VfBcNJrlbqcq8hgeChv-lAwoj1L0VoJ?usp=sharing): Fazer um codigo na mão para calcular K=2,K=3 e K=4 com memoria global e N=2 e N=4. [link git base inicial](https://github.com/canesche/kmeans/tree/main/gpu/kmeans-ricardo)
* Ruan: Fazer um gerador do DOT para uma dado conjunto de K 
* Ruan: Fazer um gerador codigo exemplo com k=i, k=i+1, K=i+2 simultaneos  gerar codigo GPU
* Westerley: Variar os valores de N. Fazer um template para N=32. 
@@ -98,13 +98,13 @@ Sugestão é baixar os codigos com git para o colab. Navegar na pasta, compilar
[Secao Thrust do MiniCurso WSCAD 2019](https://colab.research.google.com/drive/17IslqFWtsMhYXqOaeA8vP6cRgmDpkJGM?usp=sharing)
Ir na secao Thrust.

1. [Leonardo](https://colab.research.google.com/drive/1A3b9Au0OHD8rakHy7LOQ1u8XUBhxOR1r?usp=sharing) - Criar um colab separado. Fazer a tabela SORT (executar 3 vezes) com os campos: tamanho vetor, tempo, tempo transfer, Sort/s, GPU. Se possivel executar em 2 GPU com os tamanhos: 1M,2M, ....ate' maximo que a GPU e Thrust permitir.  Fazer o teste para INT, FLOAT e DOUBLE. 

2. Lucas - Buscar um Sort em CPU (codigo Radix ou Quicksort) para comparar  - [link](https://cs.stackexchange.com/questions/3/why-is-quicksort-better-than-other-sorting-algorithms-in-practice)

3. Westerley - Comparar o Thrust Transformer com um kernel de polinomio para equacoes com 10, 15 e 20 ops.

4. [Leonardo](https://colab.research.google.com/drive/1A3b9Au0OHD8rakHy7LOQ1u8XUBhxOR1r?usp=sharing) - fazer um colab para comparar a REDUCAO do Thrust com o codigo do Capitulo 4 do reduction com Unroll. vetores de tamanho 16M-64M

5. Lucas - fazer uma funcao Count em CUDA e comparar com o desempenho do [Thrust](https://docs.nvidia.com/cuda/thrust/index.html)

@@ -126,7 +126,7 @@ Ir na secao Thrust.
5. [Alexnet pytorch](https://github.com/dansuh17/alexnet-pytorch/blob/d0c1b1c52296ffcbecfbf5b17e1d1685b4ca6744/model.py#L40)

### Tarefas 
 1. [Leonardo]() - Colab: Versão CPU versus versão GPU v1 (pagina 278) versus v3 (pagina 282-84), 
 2. Ruan - Colab: versao naive matriz 227x227x3 com 96 chamadas de filtros 11x11x3 (camada 1 da alexnext) usando "v3" shared
 3. Lucas - Colab: versao [executeFirstLayer](https://github.com/pratikpv/alexnet/blob/master/GPU/cuda/an_kernel.cu)
 4. Westerley - Buscar implementações de ALEXNET com Shared
@@ -139,7 +139,7 @@ Ir na secao Thrust.

[Artigo clássico](http://developer.download.nvidia.com/CUDA/CUDA_Zone/papers/gpu_3dfd_rev.pdf)

1. [Leonardo]() - Fazer este problema no Matlab e medir o tempo. Stencil 3D. Sequencial 0, 1, 2..  256\*256\*256 = 16M
2. Lucas - Versao em CPU com FOR e usar flag vetorizacao (AVX) e OpenMP (k40) para ver ser paraleliza automatico
3. Westerley - Versao em GPU naive com FOR em "z" e comparar com a versao do artigo
4. Ruan - Adaptar tecnica do Stencil a convolucao
Toggle all file notes
Toggle all file annotations
