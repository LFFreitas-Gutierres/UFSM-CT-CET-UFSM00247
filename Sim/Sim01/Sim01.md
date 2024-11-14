![](Header.png "UFSM-CT-DESP-UFSM00247")

# UFSM00247 (Eletromagnetismo)

**Docente:** [Prof. Dr. Luiz Fernando Freitas-Gutierres](https://www.linkedin.com/in/lffreitas-gutierres/) ([luiz.gutierres@ufsm.br](mailto:luiz.gutierres@ufsm.br)).

## Simulação 01

**Leia com atenção as instruções abaixo.**

Considere um cilindro infinitamente longo com raio $a$ cm, posicionado ao longo do eixo-$z$ de um sistema de coordenadas cartesianas. O cilindro está carregado de forma uniforme, com uma densidade volumétrica de carga elétrica igual a $\rho$ C/m3. Com base nessas premissas, responda às seguintes proposições:

1. Demonstre, utilizando argumentos de simetria, que o campo elétrico é radial tanto no interior quanto no exterior do cilindro.
2. Aplicando a Lei de Gauss, determine a magnitude do campo elétrico como função de $r$, para $0 \leq r \leq a$ e para $r > a$. Em seguida, esboce um gráfico do campo elétrico no intervalo $0 \leq r < \infty$.
3. Com base na análise do item anterior, calcule a diferença de potencial elétrico entre um ponto $A$, localizado a uma distância $r$ do eixo-$z$, e um ponto $B$ situado no eixo-$z$ (assuma que os pontos estão alinhados para simplificação). Posteriormente, esboce um gráfico do potencial elétrico no intervalo $0 \leq r < \infty$.
4. Após a resolução analítica dos itens anteriores, realize simulações no [*Finite Element Method Magnetics* (FEMM), versão 4.2](https://www.femm.info/wiki/HomePage) e compare os resultados obtidos.

**Observações:**

- Respeitar as modificações de parâmetros estipuladas para cada discente na tabela abaixo.
- As propriedades que não foram explicitamente enunciadas, mas que são essenciais para a solução e/ou modelagem adequada deste problema, devem ser estabelecidas por cada discente e devidamente apresentadas no relatório.
- Utilizar, obrigatoriamente, o modelo de relatório proposto para esta atividade.
- Enviar o arquivo do relatório no formato PDF e, compactados para ZIP, os arquivos de simulação e/ou *scripts* desenvolvidos. Empregue este formato para nomear os arquivos:
    - Para o relatório: `PrimeiroNomeÚltimoSobrenome-Sim01-Rel.pdf`. Exemplo: Fulano de Beltrano Sicrano $\rightarrow$ `FulanoSicrano-Sim01-Rel.pdf`.
    - Para o arquivo ZIP: `PrimeiroNomeÚltimoSobrenome-Sim01-Arq.zip`. Exemplo: Fulano de Beltrano Sicrano $\rightarrow$ `FulanoSicrano-Sim01-Arq.zip`.

| Discente   | $a$ | $\rho$ |
|:----------:|:---:|:------:|
| 202310012  | 1,0 | 0,20   |
| 202212015  | 2,0 | 2,20   |
| 2020520156 | 3,0 | 0,40   |
| 202310092  | 4,0 | 2,40   |
| 202110403  | 5,0 | 0,60   |
| 202310097  | 6,0 | 2,60   |
| 202212237  | 7,0 | 0,80   |
| 201920744  | 8,0 | 2,80   |
| 202310748  | 9,0 | 1,00   |
| 202221521  | 1,5 | 3,00   |
| 202310917  | 2,5 | 1,20   |
| 201920831  | 3,5 | 3,20   |
| 2022510061 | 4,5 | 1,40   |
| 202311003  | 5,5 | 3,40   |
| 2022520161 | 6,5 | 1,60   |
| 201920838  | 7,5 | 3,60   |
| 201920141  | 8,5 | 1,80   |
| 202311041  | 9,5 | 3,80   |
| 202312129  | 0,5 | 2,00   |
| 202311183  | 0,7 | 4,00   |