# Graduação em Matemática Aplicada e Ciência de Dados  
**Álgebra Linear Numérica**  
Bernardo Freitas Paulo da Costa  
Monitora: Beatriz Lúcia Teixeira de Souza  

## Projeto 4  
### Álgebra Linear e Matrizes Aleatórias  
**para 21 de Junho de 2025**  

---

**Instruções:**  
- Justifique seu raciocínio e escreva respostas completas.  
- Os resultados de questões anteriores podem ser usados nas questões seguintes.  
- Explique seu código e comente os gráficos: *um gráfico sem referência no texto está "perdido"*.  

---

### Questão 1. Matrizes Gaussianas  
Uma matriz gaussiana tem todas as entradas $A_{ij}$ independentes e distribuídas segundo uma normal padrão, ou seja, $A_{ij} \sim \mathcal{N}(0,1)$.  

**a) Distribuição das normas.**  
Faça um histograma da norma-2 das colunas de uma matriz gaussiana $A_{m \times n}$. Use vários valores de $m$, e comente o que você observa.  

**b) Produtos internos.**  
Fixe $m = 100$ e faça o histograma do produto interno $\langle A_i, A_j \rangle$ entre colunas de uma matriz gaussiana $A$. Exclua os casos $i = j$, e use $n = 100$, 200, 500 e 1000. O que acontece? Qual parece ser a distribuição para $n \to \infty$?  

**c) A distribuição do máximo.**  
Queremos ver quão "não ortogonal" é a matriz $A$. Para isto, gere $K = 1000$ matrizes gaussianas $A_k$ de ordem $100 \times 300$, calcule o máximo de $\frac{|\langle A_i, A_j \rangle|}{||A_i|| \cdot ||A_j||}$ entre colunas distintas, e faça um histograma dos $K$ valores obtidos.  

**d) Complexidade computacional.**  
Qual a complexidade de calcular o máximo acima? Qual valor de $K$ seria bom para ter uma boa estimativa do máximo esperado?  

**e) A distribuição do máximo, parte 2.**  
Escolha valores de $K$ correspondentes e faça histogramas (comente os resultados) para os pares:  
- $(m,n) = (100, 100)$, $(100, 300)$  
- $(200, 200)$, $(200, 600)$  
- $(500, 500)$, $(500, 1500)$  
- $(1000, 1000)$, $(1000, 3000)$  