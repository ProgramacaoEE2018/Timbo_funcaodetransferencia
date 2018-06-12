Timbo_funcaodetranferencia

Objetivo: receber como entrada a função de transferência de um circuito H(s) e dar como saída o gráfico do polinômio do denominador e dizer se o circuito é estável ou não e dar uma breve explicação do motivo.

Motivação: saber se um circuito é estável ou não de forma prática.

O seguinte tutorial foi utilizado: https://www.youtube.com/watch?v=3YLYMtBmqEI

Escolhi a interface gráfica do matlab app designer, então, seguindo o tutorial construi um programa que plota a função sin(a*x), onde o usuário escolhe o valor de "a". Como segue o exemplo de sin(2x):
![tutorial](https://github.com/ProgramacaoEE2018/Timbo_funcaodetransferencia/blob/master/tutorial.JPG)

Esboço do projeto:
![esboço](https://github.com/ProgramacaoEE2018/Timbo_funcaodetransferencia/blob/master/esbo%C3%A7o.JPG)

A priori, o usuário coloca os coefecientes do polinômios e clica em "Play", dai o programa gera o gráfico do polinômio do denominador, e também mostra os valores das raízes e dos polos e analisa a estabilidade do circuito e dá uma breve explicação do motivo de ser estável ou não.

Para utilizar o programa, precisa de uma versão posterior a R2015b do matlab. Basta baixar e abrir o arquivo Funcaodetransferencia.mlapp que foi feito o upload aqui no github que abrirá o matlab em si e o app do programa. Para ver o código do programa deve-se abrir pelo matlab o programa daí abrirá a parte de appdesigner do matlab e então terá a parte do design e a parte do código.

Programa ainda não está finalizado mas tá bem próximo disso, falta utilizar a orientação a objeto e ajustar um caso específico de estabilidade.
