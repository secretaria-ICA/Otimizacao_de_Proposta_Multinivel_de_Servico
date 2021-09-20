# Otimização de proposta multinível de serviço

#### Aluno: [Raphael Faria Richter](https://github.com/richterraphael)
#### Orientador(/a/es/as): [Felipe Borges](https://github.com/FelipeBorgesC).

---

Trabalho apresentado ao curso [BI MASTER](https://ica.puc-rio.ai/bi-master) como pré-requisito para conclusão de curso e obtenção de crédito na disciplina "Projetos de Sistemas Inteligentes de Apoio à Decisão".


---

### Resumo

O objetivo do trabalho desenvolvido foi criar um método de otimização do estudo de troca de modelo de cobrança de um determinado serviço de um modelo de cobrança aberto, para um modelo agrupado por níveis, atendendo a padrões de distribuição e realizando a manutenção do mesmo montante financeiro envolvido.

A troca de modelo, realizada de forma racional e sem tratamentos comerciais, é realizada com estudos em báses históricas e seleções especificas para compor apenas as informações pertinentes ao serviço selecionado e sua composição.

Com a base preparada, o modelo consiste em utilizar a distribuição da população por níveis de classificação especifica do negócio e propor valores do serviço progressivamente em cada nível de forma que o ticket geral da população, tal qual o montante financeiro envolvido, seja mantido. Para tal, foram estabelecidas punições que moldavam os valores dos níveis em progressão dentro de um padrão estipulado e que garantem a manutenção de ticket e montante financeiro. 

Para encontrar valores que atendam ao modelo acima foi utilizada a ferramenta Solver do Excel. Uma equação derivada do ticket e distribuição também define limites para as variáveis, que são os valores por níveis, para reduzir o universo de testes em cada um deles. O objetivo é definido como menor valor possível, que significa a menor quantidade de punições recebidas e assim mais aderente as regras estabelecidas.

A utilização da ferramenta trouxe ótimos resultados, definindo valores que atendem às condições e expectativas, em um curto espaço de tempo. Ainda assim, há espaço para melhorias na parametrização dos limites que em algumas oportunidades requerem ajustes manuais para resolver alguns casos.

---

Matrícula: 191.671.060

Pontifícia Universidade Católica do Rio de Janeiro

Curso de Pós Graduação *Business Intelligence Master*
