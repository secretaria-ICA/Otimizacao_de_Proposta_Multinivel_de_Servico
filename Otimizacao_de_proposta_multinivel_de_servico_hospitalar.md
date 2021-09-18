# Otimização de proposta multinível de serviço hospitalar

#### Aluno: [Raphael Faria Richter](https://github.com/richterraphael)
#### Orientador(/a/es/as): [Felipe Borges](https://github.com/FelipeBorgesC).

---

Trabalho apresentado ao curso [BI MASTER](https://ica.puc-rio.ai/bi-master) como pré-requisito para conclusão de curso e obtenção de crédito na disciplina "Projetos de Sistemas Inteligentes de Apoio à Decisão".


---

### Resumo

O objetivo do trabalho desenvolvido foi criar um método de otimização do estudo de troca de modelo de cobrança de um determinado serviço hospitalar de um modelo fee for service, para um modelo agrupado por níveis, atendendo a padrões de distribuição e realizando a manutenção do mesmo montante financeiro envolvido.

A troca de modelo, realizada de forma racional e sem tratamentos comerciais, é realizada com estudos em báses históricas e seleções especificas para compor apenas as informações pertinentes ao serviço selecionado e sua composição.

Com a base preparada, é observado tanto o montante geral da população quanto a distribuição geral e por níveis, pré estabelecidos por classificação médica, para discriminar o ticket dessa popoulação. Na sequência com a distribuição observado pelos níveis é necessário estabelecer o valor do serviço de cada nível de forma que tanto o ticket quanto o montante observado ao final dessa definição sejam iguais ou o mais próximo do observado inicialmente. Para atender a esse objetivo e se enquandrar no parâmetro de progessão razoável de valores entre os níveis, foi pensado uma equação que impõe pesos a essas transgressões e as soma como punições aos pontos estabelecidos acima. Isso tende ao melhor resultado quando seu valor é mais próximo de 0, ou seja, o menor número de transgressões e por consequência de punições. E para encontrar um grupo de valores que atenda satisfatóriamente todas as condições citadas, foi utilizada a ferramenta Solver do Excel, com definição de limites progressivos e derivados do ticket médio em cada nível para reduzir o universo de testes em cada um deles.

A utilização da ferramenta trouxe ótimos resultados, definindo valores que atendem às condições e expectativas, em um curto espaço de tempo. Ainda assim, há espaço para melhorias na parametrização dos limites que em algumas oportunidades requerem ajustes manuais para resolver alguns casos.

---

Matrícula: 191.671.060

Pontifícia Universidade Católica do Rio de Janeiro

Curso de Pós Graduação *Business Intelligence Master*
