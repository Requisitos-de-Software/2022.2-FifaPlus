# Backlog de produto

## 1. Introdução

Um dos principais artefatos da metodologia de desenvolvimento de software SCRUM para a modelagem de requisitos é o chamado *backlog de produto* (backlog do produto). Ele tem como objetivo acordar as necessidades do produto como um todo.

O *backlog de produto* é uma lista contendo as funcionalidades desejadas para o produto. Podem fazer parte do *backlog de produto* tanto tarefas técnicas como atividades diretamente relacionadas às funcionalidades.

Nas seções seguintes, definimos o modelo de representação e apresentamos o *backlog de produto* produzido pelo grupo a respeito do aplicativo FIFA+, objeto de estudo do projeto

## 2. Metodologia

### 2.1. Estrutura
Para o *backlog de produto*, utilizaremos as seguintes categorias para facilitar a descrição das funcionalidades e histórias de usuário:

- **Épico:** Conjunto de funcionalidades que tem pontos em comum ou fazem parte de um mesmo módulo
- **Feature:** A funcionalidade descrita
- **Rastreabilidade:** Os requisitos já listado ao qual a feature e a história de usuário estão relacionadas
- **ID:** Sigla para identificar e listar as histórias de usuário
- **História de usuário:** (US - *User story*) Detalhamento do item e contextualização da utilidade da funcionalidade
- **Prioridade**: A prioridade dos requisitos relacionados

### 2.2. Tabela de modelo
Na Tabela 1, apresentamos o modelo a ser utilizado para descrever o *product blacklog*:

<div align="center" style="text-align: center">
<p>Tabela 1: Modelo para o backlog de produto</p>
</div>

| Épico              | Feature              | US_ID                                | História de usuário | Rastreabilidade               |
| :----------------- | :------------------- | :----------------------------------- | :------------------ | :---------------------------- |
| O épico em questão | A feature em questão | O ID utilizado para identificar a US | Nome da US          | O ID do requisito relacionado |

<div align="center" style="text-align: center">
<p>Fonte: Autoria própria</p>
</div>

## 3. Épicos

Com base nas histórias de usuários desenvolvidas, nas funcionalidades (features), e nas áreas de atuação identificadas durante a apresentação dos resultados da elicitação, foi possível agrupar as funcionalidades em 4 épicos, que podem ser visualizados na (Tabela 2):


<div align="center" style="text-align: center">
<p>Tabela 2: Épicos</p>
</div>

| ID  | Épico       | Descrição                                                                                            |
| :-- | :---------- | :--------------------------------------------------------------------------------------------------- |
| E01 | Usuário     | Engloba as funcionalidades de cadastro e de login que possibilitam acesso ao sistema.                |
| E02 | Informações | Engloba as funcionalidades de visualização de informações e estatísticas sobre equipes na competição |
| E03 | Jogos       | Engloba as funcionalidades de visualização de informações e estatísticas sobre jogos                 |
| E04 | Mídia       | Engloba as funcionalidades de transmissão e reprodução de mídia sobre os jogos                       |

<div align="center" style="text-align: center">
<p>Fonte: Autoria própria</p>
</div>

## 4. Backlog de Produto

Na Tabela 3, apresentamos o *backlog de produto* produzido.

<div align="center" style="text-align: center">
<p>Tabela 3: Backlog de Produto</p>
</div>

<style type="text/css">
.tg  {border-collapse:collapse;border-color:#ccc;border-spacing:0;}
.tg td{background-color:#fff;border-color:#ccc;border-style:solid;border-width:1px;color:#333;
  font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{background-color:#f0f0f0;border-color:#ccc;border-style:solid;border-width:1px;color:#333;
  font-family:Arial, sans-serif;font-size:14px;font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-tlc1{background-color:#9883de;border-color:#9883de;color:#ffffff;text-align:center;vertical-align:middle}
.tg .tg-02dx{background-color:#f9f9f9;border-color:#cccccc;color:#333333;text-align:center;vertical-align:middle}
.tg .tg-uvo0{background-color:#9883de;border-color:#9883de;color:#ffffff;font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-d5nr{background-color:#f9f9f9;border-color:#cccccc;text-align:center;vertical-align:middle}
.tg .tg-m932{background-color:#f9f9f9;border-color:#cccccc;color:#002b36;text-align:center;vertical-align:middle}
.tg .tg-i9zc{border-color:#cccccc;text-align:center;vertical-align:middle}
.tg .tg-tobj{border-color:#cccccc;color:#002b36;text-align:center;vertical-align:middle}
.tg .tg-beto{border-color:#cccccc;color:#333333;text-align:center;vertical-align:middle}
</style>
<table class="tg" style="undefined; width: 100%">
<colgroup>
<col style="width: 109px">
<col style="width: 109px">
<col style="width: 79px">
<col style="width: 166px">
<col style="width: 143px">
</colgroup>
<thead>
  <tr>
    <th class="tg-tlc1"><span style="font-weight:bold">Épico</span></th>
    <th class="tg-uvo0"><span style="font-weight:700">Feature</span></th>
    <th class="tg-uvo0"><span style="font-weight:700">US_ID</span></th>
    <th class="tg-uvo0">História de usuário</th>
    <th class="tg-uvo0"><span style="font-weight:700">Rastreabilidade</span></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-d5nr" rowspan="8">Usuário</td>
    <td class="tg-d5nr" rowspan="8">Cadastro e Login</td>
    <td class="tg-m932" rowspan="3">US01</td>
    <td class="tg-m932" rowspan="3">Criação de conta</td>
    <td class="tg-d5nr">B27</td>
  </tr>
  <tr>
    <td class="tg-i9zc">B28</td>
  </tr>
  <tr>
    <td class="tg-d5nr">B29</td>
  </tr>
  <tr>
    <td class="tg-tobj" rowspan="5">US02</td>
    <td class="tg-tobj" rowspan="5">Fazer login</td>
    <td class="tg-i9zc">B30</td>
  </tr>
  <tr>
    <td class="tg-d5nr">B31</td>
  </tr>
  <tr>
    <td class="tg-i9zc">B32</td>
  </tr>
  <tr>
    <td class="tg-d5nr">B33</td>
  </tr>
  <tr>
    <td class="tg-i9zc">OB09</td>
  </tr>
  <tr>
    <td class="tg-d5nr" rowspan="4">Informações</td>
    <td class="tg-d5nr" rowspan="4">Equipes</td>
    <td class="tg-02dx">US03</td>
    <td class="tg-02dx">Ver Seleções</td>
    <td class="tg-d5nr">OB06</td>
  </tr>
  <tr>
    <td class="tg-beto">US04</td>
    <td class="tg-beto">Ver Notícias</td>
    <td class="tg-i9zc">B19</td>
  </tr>
  <tr>
    <td class="tg-02dx" rowspan="2">US05</td>
    <td class="tg-02dx" rowspan="2">Ver Estatísticas</td>
    <td class="tg-d5nr">B22</td>
  </tr>
  <tr>
    <td class="tg-i9zc">B23</td>
  </tr>
  <tr>
    <td class="tg-d5nr" rowspan="3">Jogos</td>
    <td class="tg-d5nr" rowspan="3">Pontuação e Jogos</td>
    <td class="tg-m932">US06</td>
    <td class="tg-m932">Ver Calendário</td>
    <td class="tg-d5nr">OB07</td>
  </tr>
  <tr>
    <td class="tg-tobj" rowspan="2">US07</td>
    <td class="tg-tobj" rowspan="2">Ver Classificação</td>
    <td class="tg-i9zc">B24</td>
  </tr>
  <tr>
    <td class="tg-d5nr">B25</td>
  </tr>
  <tr>
    <td class="tg-i9zc" rowspan="13">Mídia</td>
    <td class="tg-i9zc" rowspan="13">Transmissão e Vídeos</td>
    <td class="tg-tobj" rowspan="3">US08</td>
    <td class="tg-tobj" rowspan="3">Ver Melhores Momentos</td>
    <td class="tg-i9zc">B03</td>
  </tr>
  <tr>
    <td class="tg-d5nr">B04</td>
  </tr>
  <tr>
    <td class="tg-i9zc">B05</td>
  </tr>
  <tr>
    <td class="tg-m932" rowspan="5">US09</td>
    <td class="tg-m932" rowspan="5">Replay dos Jogos</td>
    <td class="tg-d5nr">OB01</td>
  </tr>
  <tr>
    <td class="tg-i9zc">OB03</td>
  </tr>
  <tr>
    <td class="tg-d5nr">OB04</td>
  </tr>
  <tr>
    <td class="tg-i9zc">OB05</td>
  </tr>
  <tr>
    <td class="tg-d5nr">OB10</td>
  </tr>
  <tr>
    <td class="tg-tobj" rowspan="5">US10</td>
    <td class="tg-tobj" rowspan="5">Ver Jogos ao Vivo</td>
    <td class="tg-i9zc">OB01</td>
  </tr>
  <tr>
    <td class="tg-d5nr">OB03</td>
  </tr>
  <tr>
    <td class="tg-i9zc">OB04</td>
  </tr>
  <tr>
    <td class="tg-d5nr">OB05</td>
  </tr>
  <tr>
    <td class="tg-i9zc">OB10</td>
  </tr>
</tbody>
</table>

<div align="center" style="text-align: center">
<p>Fonte: Autoria própria</p>
</div>

## 4. Referências

> - SERRANO, Milene; SERRANO, Maurício. Requisitos (Aula 15): Elicitação, Modelagem e Análise. 2022. Apresentação de Power Point. 46 slides. color. Disponível em: https://aprender3.unb.br/pluginfile.php/2307525/mod_resource/content/1/Requisitos%20-%20Aula%2015a.pdf. Acesso em: 30 dez. 2022.

## 5. Histórico de Versão
|    Data    | Versão |                                Descrição                                 |         Autor          | Revisor |
| :--------: | :----: | :----------------------------------------------------------------------: | :--------------------: | :-----: |
| 30/12/2022 |  1.0   |                    Descrição da metodologia e modelos                    | Charles Serafim Morais | Thiago  |
| 04/01/2022 |  1.1   | Adição dos épicos, histórias de usuário e demais informações nas tabelas |      Eric Chagas       | Thiago  |

