## Análise financeira do McDonalds

![Static Badge](https://img.shields.io/badge/python-%233776AB?style=for-the-badge&logo=python&logoColor=white)
![Static Badge](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Static Badge](https://img.shields.io/badge/pandas-%23150458?style=for-the-badge&logo=pandas&logoColor=white)
![Static Badge](https://img.shields.io/badge/matplotlib-%23135F9B?style=for-the-badge)
![Static Badge](https://img.shields.io/badge/seaborn-%23444876?style=for-the-badge)

![img](imagens/cover.jpg)

O objetivo do projeto é analisar os dados financeiros do McDonald's para avaliar o desempenho da empresa em termos de capitalização de mercado, receita, lucro, e outros indicadores financeiros ao longo do tempo. O projeto visa entender a saúde financeira da empresa e identificar tendências, padrões e áreas de melhoria, com foco nos seguintes aspectos:

- Tendência na Capitalização de Mercado: Avaliar como a capitalização de mercado do McDonald's tem mudado ao longo dos anos.

- Crescimento da Receita e Lucro: Analisar o crescimento da receita e dos lucros da empresa para determinar se a empresa está expandindo ou enfrentando dificuldades financeiras.

- Índices de Rentabilidade: Examinar os índices financeiros, como o P/E (preço/lucro), P/S (preço/vendas), e P/B (preço/valor patrimonial) para avaliar o valor relativo das ações da empresa.

- Posições de Caixa: Avaliar a quantidade de dinheiro disponível da empresa e suas reservas de caixa para entender sua liquidez e capacidade de enfrentar imprevistos financeiros.

- Níveis de Dívida e Obrigações: Analisar a dívida total e as obrigações da empresa para avaliar sua estrutura de capital e níveis de risco financeiro.

O objetivo final é proporcionar uma visão abrangente sobre a saúde financeira da McDonald's e sua posição no mercado, ajudando a identificar se a empresa está indo bem ou se há áreas que necessitam de atenção.

## Dúvidas

- Como a capitalização de mercado, receita e lucro do McDonald's evoluíram ao longo dos anos?
- Qual é a relação entre a margem operacional, o EPS e o lucro do McDonald's?
- O que o índice P/E do McDonald's revela sobre as expectativas do mercado ao longo dos anos?
- Como a dívida do McDonald's se comportou em relação aos seus ativos totais ao longo dos anos?
- Como o rendimento de dividendos e os dividendos ajustados do McDonald's evoluíram ao longo dos anos, e o que isso indica sobre a confiança dos investidores?
- A capitalização de mercado do McDonald's reflete seu desempenho financeiro ao longo dos anos?
- O que a variação do P/B ratio ao longo dos anos indica sobre a avaliação do McDonald's pelo mercado?

## Sobre o Conjunto de Dados

A McDonald’s Corporation é uma operadora e franquia americana de restaurantes de fast food com representação mundial e a maior empresa de fast food do mundo. Fundada em 1940 por Richard e Maurice MacDonald, a empresa cresceu significativamente e desempenhou um papel fundamental na formação da indústria de fast food. A marca se orgulha de oferecer alimentos consistentes, rápidos e acessíveis. De acordo com nossos dados, o McDonald's é a 51ª empresa mais valiosa do mundo por capitalização de mercado. A empresa teve uma receita de 23,18 bilhões em 2022, comparada à receita de 23,22 bilhões em 2021.

Os dados contêm as seguintes colunas:

`Ano:` O ano para o qual os dados financeiros foram reportados.

`Capitalização de Mercado:` Valor total de mercado das ações do McDonald's. Mostra quanto a empresa vale no mercado de ações.

`Receita:` Total de dinheiro que o McDonald's ganha com a venda de seus produtos, sem descontar despesas.

`Lucro:` Dinheiro que o McDonald's ganha antes de pagar impostos.

`P/E Ratio (Índice Preço/Lucro):` Mede o preço das ações do McDonald's em relação ao lucro. Ajuda a avaliar se as ações estão caras ou baratas.

`P/S Ratio (Índice Preço/Vendas):` Mede o preço das ações em relação às vendas. Mostra se as ações estão caras ou baratas comparado ao volume de vendas da empresa.

`P/B Ratio (Índice Preço/Valor Patrimonial):` Compara o preço das ações com o valor patrimonial da empresa. Ajuda a ver se as ações estão sobrevalorizadas ou subvalorizadas.

`Margem Operacional:` Percentual de lucro obtido com as vendas, depois de descontar todos os custos operacionais como matérias-primas e aluguel.

`EPS (Lucro por Ação):` Lucro líquido da empresa dividido pelo número de ações. Mostra quanto cada ação contribui para o lucro.

`Número de Ações em Circulação:` Quantidade total de ações do McDonald's que estão disponíveis no mercado.

`Caixa em Mão:` Quantia de dinheiro disponível que o McDonald's possui, incluindo dinheiro e investimentos de curto prazo.

`Rendimento de Dividendos:` Histórico de quanto o McDonald's paga aos acionistas como dividendos.

`Dividendo (ajustado por desdobramento de ações):` Histórico de dividendos pagos, ajustado para refletir desdobramentos de ações.

`Ativos Líquidos:` Total dos ativos do McDonald's menos suas obrigações. Mostra o valor real dos ativos da empresa.

`Ativos Totais:` Soma de todos os ativos do McDonald's, incluindo dinheiro, inventários e propriedades.

`Dívida Total:` Total das dívidas do McDonald's, tanto correntes quanto de longo prazo.

`Obrigações Totais:` Total das dívidas e compromissos do McDonald's, incluindo todas as obrigações financeiras.

`($B):` Símbolo para bilhões de dólares.

## Análise Exploratória

**Análise de Tendências**
- A tendência da capitalização de mercado parece estar a aumentar ao longo dos anos, o que sugere um sentimento positivo dos investidores e perspectivas de crescimento. As receitas e os lucros revelaram uma tendência global crescente ao longo dos anos, com algumas flutuações. Isto indica que a empresa tem sido capaz de aumentar as suas receitas e resultados ao longo do tempo.

![img](imagens/1.png)

---

**Análise de Correlação**

![img](imagens/2.png)

---

**Comparação de Métricas de Desempenho**
![img](imagens/3.png)

---

**Análise de Ratios**
- P/E Ratio , P/S Ratio e P/B Ratio: P/E Ratio (Índice Preço/Lucro) apresenta flutuações ao longo dos anos, mas geralmente permanece dentro de um intervalo razoável. P/S Ratio (Índice Preço/Vendas) também apresenta flutuações, mas mostra uma tendência relativamente estável. P/B Ratio (Índice Preço/Valor Patrimonial) Apresenta alguns valores negativos, indicando potenciais problemas com o cálculo do valor contabilístico.

![img](imagens/4.png)

---

**Visualização das receitas, os ganhos e o dinheiro em caixa ao longo dos anos**
- As disponibilidades registam algumas flutuações, mas, em geral, seguem uma tendência crescente ao longo dos anos. Este facto sugere que a empresa tem sido capaz de manter ou melhorar a sua posição de liquidez.

![img](imagens/5.png)

---

**Gráfico de barras comparando o rendimento dos dividentos em diferentes anos**

![img](imagens/6.png)

---

**Gráfico de dispersão que mostra a relação entre o P/E ratio e EPS**

![img](imagens/7.png)

---

**Calculando os níveis de despesas e as responsabilidades ao longo do ano**

- A dívida total e o passivo total aumentaram ao longo dos anos, o que pode indicar um aumento da alavancagem e das obrigações financeiras.

- Rendibilidade do capital próprio (ROE): O ROE mede a rentabilidade de uma empresa, revelando o lucro que a empresa gera com o dinheiro que os accionistas investiram.

- Rácio de dívida para capital próprio: O rácio indica a proporção de capital próprio e de dívida utilizada para financiar as afirmações de uma empresa.

- Fluxo de caixa livre (FCF): O FCF representa o dinheiro que uma empresa é capaz de gerar depois de ter desembolsado o dinheiro necessário para manter ou expandir a sua base de activos. É calculado como o fluxo de caixa operacional menos as despesas de capital.

![img](imagens/8.png)

---

**Projeção do ROE ao longo dos anos**

![img](imagens/9.png)

---

**Traçar o rácio entre a dívida e o capital próprio ao longo dos anos**

- Embora o conjunto de dados revele tendências positivas em termos de capitalização de mercado, receitas e lucros, existem flutuações e desafios em termos de rendibilidade, margem operacional e níveis de endividamento merecem uma análise mais aprofundada.

![img](imagens/10.png)

---

**Tendência Geral dos Indicadores (Market Cap, Revenue, Earnings)**

- Ao longo dos anos analisados, o McDonald's demonstrou um crescimento consistente em sua capitalização de mercado e em seus lucros. Mesmo diante de flutuações econômicas, a empresa manteve uma trajetória ascendente, indicando resiliência e forte presença no mercado

![img](imagens/11.png)

---

**Margem Operacional e EPS vs Lucro**

- A margem operacional e o lucro por ação (EPS) apresentaram uma correlação positiva com o lucro líquido. Isso sugere que o McDonald's conseguiu manter uma boa eficiência operacional, convertendo suas operações em lucros consistentes para os acionistas.

![img](imagens/12.png)

---

**P/E Ratio**

- O índice P/E variou ao longo dos anos, sugerindo diferentes expectativas do mercado quanto ao crescimento futuro do McDonald's. Picos no P/E podem indicar que o mercado esperava um crescimento significativo, mas também podem refletir uma possível sobrevalorização da empresa em determinados períodos.

![img](imagens/13.png)

---

**Dívida em relação aos Ativos Totais**

- A relação entre dívida e ativos totais permaneceu relativamente estável ao longo dos anos, indicando uma alavancagem financeira controlada. Isso sugere que o McDonald's tem gerido sua estrutura de capital de forma prudente, embora o aumento gradual da dívida mereça atenção contínua.

![img](imagens/14.png)

---

**Rendimento de Dividendos e Confiança do Investidor**

- Tanto o rendimento de dividendos quanto os dividendos ajustados por ação aumentaram consistentemente, refletindo a confiança dos investidores na sustentabilidade financeira do McDonald's e seu compromisso em retornar valor aos acionistas.

![img](imagens/15.png)

---

**Capitalização de Mercado e Desempenho Financeiro**

- A capitalização de mercado do McDonald's acompanhou de perto as tendências de receita, lucro e ativos totais, sugerindo que o mercado avalia a empresa de forma consistente com seu desempenho financeiro.

![img](imagens/16.png)

---

**Relação Valor de Mercado e Valor Contábil (P/B ratio)**

- O P/B ratio do McDonald's apresentou variações, incluindo valores negativos em alguns anos, o que pode indicar desafios financeiros ou uma percepção de risco elevado. Isso sugere que, em determinados períodos, o mercado avaliou a empresa abaixo de seu valor contábil, possivelmente devido a incertezas ou dificuldades enfrentadas.

## Considerações Finais

É possível notar que o McDonald's é uma empresa com forte desempenho, marcada por crescimento consistente e uma gestão eficiente de operações. No entanto, as flutuações nos índices de avaliação, como o P/E e o P/B, sugerem que o mercado teve percepções variáveis sobre o futuro da empresa em diferentes períodos. A alavancagem financeira e a dívida devem ser monitoradas para garantir a sustentabilidade a longo prazo. O compromisso da empresa em aumentar os dividendos reflete confiança em sua capacidade de gerar valor contínuo para os acionistas.

Esses insights fornecem uma visão abrangente da saúde financeira da McDonald's e podem servir de base para decisões estratégicas futuras.

