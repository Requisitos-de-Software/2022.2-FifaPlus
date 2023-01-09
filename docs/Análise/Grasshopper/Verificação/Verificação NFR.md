# Verificação NFR


## 1. Introdução
<p align="justify">&emsp;&emsp;"Verificação e Validação de Software é uma abordagem 
disciplinada para avaliação dos produtos de software ao longo do ciclo de vida do 
produto. V&V se esforça para garantir que a qualidade seja incorporada ao software 
e que este satisfaça os requisitos do usuário” (IEEE1059-93).
V&V aborda diretamente a qualidade do produto de software e utiliza técnicas de 
teste para localizar defeitos que, em seguida, devem ser resolvidos. Eles também 
avaliam os produtos intermediários, e, neste caso, as etapas intermediárias dos 
processos do ciclo de vida.

O processo V&V determina se os produtos de uma certa atividade de 
desenvolvimento ou de manutenção estão em conformidade com os requisitos da 
atividade, e se o produto final de software atende à sua finalidade e satisfaz 
requisitos do usuário. Verificação é uma tentativa de garantir que o produto seja 
construído corretamente, no sentido que a atividade de desenvolvimento dos 
produtos reúne as especificações impostas em atividades anteriores. Validação é 
uma tentativa de se certificar que o produto certo foi construído, ou seja, que o 
produto específico cumpre sua função específica. Os processos de verificação e 
validação começam cedo no desenvolvimento ou fase de manutenção. Eles 
fornecem uma análise das principais funcionalidades do produto tanto em relação ao 
produto imediatamente antecessor quanto em relação a especificações às quais ele 
deve se ater.(Software Engineering Body of Knowledge"SWEBOK")
</p>


## 2. Metodologia
A metodologia a ser utilizada será a Inspeção. A inspeção é um método gerencial de reuniões as quais objetivam descobrimento de defeitos em documentos. Quando produzidos por Engenheiros de Software a sua estrutura é uma lista de requisitos.

# Checklist

Os diagramas NFR possuem elementos básicos dos NFR Framework (Fluxo, softgoals, operacionalizações, claims, contribuições).

| Questões | Motivo |
|----|-------|
| O fluxo do diagrama está bem representado? | É necessário que o fluxo seja de fácil entendimento |
| Os softgoals condizem com o contexto? | É necessário que os softgoals façam parte do contexto do aplicativo |
| Existem softgoals suficientes no diagrama para representar o contexto? | A explicação e descrição do contexto é fundamental para o entendimento do diagrama |
| Os impactos foram corretamente propagados? | Dentro do diagrama NFR, é necessário que a propagação esteja coesa e de fácil entendimento |
| As operacionalizações condizem com o contexto? | É necessário que todos os elementos do diagrama estejam de acordo com o contexto do aplicativo |
| Existem operacionalizações suficientes no diagrama para representar o contexto? | A explicação e descrição do contexto é fundamental para o entendimento do diagrama |
| Existem claims suficientes para que se entenda o diagrama? | As claims são fundamentais para o entendimento do diagrama NFR |
| As claims estão bem escritas? | O entendimento do usuário ao visualizar o diagrama deve ser rápido e fácil |
| As contribuições "AND" estão corretamente representadas e aplicadas? | Uma contribuição errada pode afetar os resultados dos requisitos |
| As contribuições "OR" estão corretamente representadas e aplicadas? |Uma contribuição errada pode afetar os resultados dos requisitos |
| As contribuições positivas estão corretamente representadas? | Uma contribuição errada pode afetar os resultados dos requisitos|
| As contribuições entre ramos diferentes estão corretamente representadas? | Uma contribuição errada pode afetar os resultados dos requisitos|

<p> Tabela 1 - Perguntas relacionadas ao checklist (Fonte: Repositório do Exercito Brasileiro).</p>


# Inspeção

| Questões | Geral | Performance | Segurança | Disponibilidade |
|--------|---|---|---|---|
| O fluxo do diagrama está bem representado? |:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|
| Os softgoals condizem com o contexto? |:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|
| Existem softgoals suficientes no diagrama para representar o contexto? |:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|
| Os impactos foram corretamente propagados?  |:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|
| As operacionalizações condizem com o contexto? |:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|
| Existem operacionalizações suficientes no diagrama para representar o contexto? |:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|
| Existem claims suficientes para que se entenda o diagrama? |:x:|:x:|:x:|:x:|
| As claims estão bem escritas? |:x:|:x:|:x:|:x:|
| As contribuições "AND" estão corretamente representadas e aplicadas? |:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|
| As contribuições "OR" estão corretamente representadas e aplicadas? |:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|
| As contribuições positivas estão corretamente representadas? |:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|
| As contribuições entre ramos diferentes estão corretamente representadas? |:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|


<p> Tabela 2 - Checklist do NFR (Fonte: Repositório do Exercito Brasileiro).</p>



## 12. Referências

> - SERRANO, Maurício; SERRANO, Milene; Requisitos - Aula 10. Acesso em: 08 de jan. de 2023;
> - (SILVA, 2019, p. 30). Acesso em: 08 de jan. de 2023.
> - Software Engineering Body of Knowledge"SWEBOK" p. 180. Acesso em: 08 de jan. de 2023.
> - Requisitos de Software - Verificação do NFR - Exercito Brasileiro. Acesso em: 08 de jan. de 2023. Disponível em:<https://github.com/Requisitos-de-Software/2022.1-Exercito-Brasileiro>;




## 13. Histórico de Versão
| Data |   Versão    |       Descrição       |     Autor     |    Revisor    |
|:------:|:----------:|:---------------------:|:-------------:|:-------------:|
|  08/01/2023  | 1.0 | Criação do escopo do documento  |     Thiago Cerqueira     | Charles |
