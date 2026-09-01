# PRECIFICA

### Sistema Inteligente de Comparação de Preços com Impostos Inclusos

## Sobre o Projeto

O **PRECIFICA** consiste em um projeto acadêmico desenvolvido em grupo no âmbito da disciplina **Fábrica de Projetos Ágeis I**, durante o 1º termo do curso de **Análise e Desenvolvimento de Sistemas (ADS)**.
A proposta foi desenvolvida em parceria com a empresa **Scaquete**, de Marília, sob direção de **Vanderley Scaquete**, tendo como finalidade aproximar o ambiente acadêmico de uma situação prática do contexto empresarial.
A priori, o desafio proposto aos grupos consistiu em investigar a relação entre **NCM (Nomenclatura Comum do Mercosul)**, **IBPT (Instituto Brasileiro de Planejamento e Tributação)** e **CEST (Código Especificador da Substituição Tributária)**, considerando o contexto da **Lei da Transparência Tributária (Lei nº 12.741/2012)**.
Nesse contexto, o PRECIFICA foi concebido como uma solução voltada à comparação de preços e à apresentação da composição tributária dos produtos, buscando transformar dados fiscais em informações úteis para consumidores e empresas.

## Objetivo

O principal objetivo do PRECIFICA é centralizar a comparação de preços de televisores e possibilitar a visualização dos valores considerando a incidência tributária.

Sob essa perspectiva, o sistema busca:
- Centralizar preços de diferentes marketplaces;
- Exibir valores com impostos inclusos;
- Facilitar a comparação entre produtos;
- Promover maior transparência tributária;
- Auxiliar consumidores na identificação do melhor custo-benefício;
- Apoiar empresas na análise de preços, custos e margens.

## Cálculo Tributário

O processo de cálculo tributário constitui uma das principais partes conceituais do projeto.
Doravante, o sistema considera a integração entre **NCM, CEST e IBPT** para estruturar a análise fiscal dos produtos.

O fluxo contempla:
1. Identificação do produto por meio do NCM;
2. Verificação do CEST;
3. Consulta do percentual estimado do IBPT;
4. Aplicação da margem de lucro;
5. Cálculo dos tributos;
6. Geração do preço sugerido;
7. Comparação com o valor praticado pelo mercado.

As principais fórmulas utilizadas são:

**Valor com lucro:**
`Custo Base + (Custo Base × Margem de Lucro / 100)`

**Valor dos tributos:**
`Valor com lucro × Percentual IBPT / 100`

**Preço sugerido:**
`Valor com lucro + Valor dos tributos`

**Comparação com o mercado:**
`[(Preço Sugerido − Valor de Mercado) / Valor de Mercado] × 100`

## NCM, CEST e IBPT

A estrutura conceitual do PRECIFICA fundamenta-se na relação entre três elementos fiscais:
- **NCM:** utilizado para a classificação fiscal dos produtos;
- **CEST:** utilizado para o enquadramento em situações relacionadas à Substituição Tributária;
- **IBPT:** utilizado como referência para os percentuais estimados da carga tributária.

Para a composição do processo, foram consideradas informações provenientes de fontes relacionadas à classificação e tributação dos produtos.

## Protótipo

O protótipo do PRECIFICA foi desenvolvido inicialmente no **Canva** e posteriormente refinado no **Figma**, contemplando as principais telas e fluxos de navegação do sistema.

O projeto visual priorizou:
- Modernidade;
- Tecnologia;
- Inteligência de dados;
- Transparência;
- Simplicidade;
- Facilidade de navegação.

📎[**Link da apresentação no figma**](https://www.figma.com/design/vniXQLkmkQ6tIxgFdSskrJ/Dev-Delas---Precifica?node-id=0-1&t=h03FvuqX0w1Q9cTv-1)

## Apresentação

A apresentação acadêmica do projeto foi desenvolvida no **Canva**, reunindo os principais conceitos, objetivos, fluxos e resultados obtidos durante o desenvolvimento.

📎[**Link da apresentação no Canva:**](https://canva.link/x1kqitzx9vtuzgp)

## Documentação

A documentação apresenta o desenvolvimento conceitual do PRECIFICA, contemplando o entendimento do problema, objetivos, cálculo tributário, diagramas, requisitos funcionais e não funcionais, regras de negócio, estrutura de dados, fluxo do usuário e propostas de evolução.

📎[**Link da documentação completa**](https://docs.google.com/document/d/1EgtC3j73qrqF9s8X8QTSZF1LInkUX2HCeibTKqqW7yk/edit?usp=sharing)

## Desenvolvimento

O projeto foi desenvolvido em equipe pelas estudantes:

- Ana Clara Gambini Nunes
- Beatriz Martins de Freitas
- Isadora Arantes de Oliveira
- Layane Valsecchi
- Julia Sgorlon Dias do Nascimento
- Sophia Melissa dos Santos de Mendonça

**Curso:** Análise e Desenvolvimento de Sistemas  
**Disciplina:** Fábrica de Projetos Ágeis I  
**Instituição:** Universidade de Marília — UNIMAR  
**Ano:** 2026

## Considerações Finais

Logo, o PRECIFICA representa uma aplicação prática dos conhecimentos desenvolvidos ao longo da disciplina, articulando **pensamento analítico, modelagem de problemas, lógica e compreensão de processos reais**.

O projeto demonstra, portanto, como informações fiscais e tributárias podem ser estruturadas para apoiar a formação de preços, ampliar a transparência e auxiliar processos de tomada de decisão.

>> **O preço informa. A transparência convence.** 