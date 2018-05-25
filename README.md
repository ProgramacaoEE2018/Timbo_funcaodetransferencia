Timbo_funcaodetranferencia

Receber como entrada a função de transferência de um circuito H(s) e dar como saída um gráfico com as raízes e os polos plotados e diz se o circuito é estável ou não e dá uma breve explicação do motivo.

Motivação: saber se um circuito é estável ou não de forma prática.

O seguinte tutorial foi utilizado: https://www.youtube.com/watch?v=3YLYMtBmqEI

Escolhi a interface gráfica do matlab app designer, então, seguindo o tutorial construi um programa que plota a função sin(a*x), onde o usuário escolhe o valor de "a". Como segue o exemplo de sin(2x):
![tutorial](https://github.com/ProgramacaoEE2018/Timbo_funcaodetransferencia/blob/master/tutorial.JPG)

Esboço do projeto:
![esboço](https://github.com/ProgramacaoEE2018/Timbo_funcaodetransferencia/blob/master/esbo%C3%A7o.JPG)

A priori, o usuário coloca o grau dos polinônios e os coefecientes do polinômios e clica em "Go", dai o programa gera o gráfico dos polinômios, marcando os polos e as raízes,( ou o gráfico da resposta natural do circuito ), e também mostra os valores dessas raízes e polos e analisa a estabilidade do circuito e da uma breve explicação do motivo de ser estável ou não.
