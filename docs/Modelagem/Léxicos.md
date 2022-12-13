# Léxicos 

## 1. Introdução
<p align="justify">&emsp;&emsp;Atividade que visa elaborar modelos capazes de representar características ou comportamentos de um software.
LAL - Léxico Ampliado da Linguagem - Trata-se de uma técnica que compõe os cenários de forma a descrever os símbolos de uma linguagem. Nesse caso, essa técnica descreve alguns termos relacionados ao software em questão. Cada símbolo tem um nome, uma noção e um impacto.</p>



<p align="justify">&emsp;&emsp;Os léxicos podem ser dividos em 3 tipos: Estado, Objeto e Verbo.</p>

## 2. Metodologia
<p align="justify">&emsp;&emsp;Após a listagem dos léxicos do tipo estado identificados pela equipe, eles foram detalhados compondo os seguintes elementos:</p>

- **Nome**: nome do léxico em si.
- **Classificação**: tipo de léxico podendo ser Estado, Objeto e Verbo  
- **Sinônimos**: palavras ou expressões com significado similar ao léxico.
- **Impacto**: identificar outros estados e ações que podem ocorrer a partir do que se descreve.
- **Noção**: o que significa e quais ações levaram a esse estado.

## 3. Léxicos 

<div id="melhores-momentos"></div>

### 3.1 - Aba De Melhores Momentos
| Elemento | Descrição |
| :------: | :-------- |
| Nome     | Melhores Momentos |
| Classificação | Objeto |
| Sinônimos| Melhores Lances, Cortes, Highlight |
| Noção    | A aba de melhores momentos é onde se localiza os [videos](https://requisitos-de-software.github.io/2022.2-FifaPlus/Modelagem/Léxicos/#videos) dos pontos altos dos jogos|
| Impacto  | Os [usuários](https://requisitos-de-software.github.io/2022.2-FifaPlus/Modelagem/Léxicos/#usuarios) podem [compartilhar](https://requisitos-de-software.github.io/2022.2-FifaPlus/Modelagem/Léxicos/#compartilhar) os melhores momentos em suas redes sociais. |



<div id="usuarios"></div>

### 3.2 - Usuários
| Elemento | Descrição |
| :------: | :-------- |
| Nome     |  Usuários |
| Classificação | Objeto |
| Sinônimos| User, Utilizador, Cliente |
| Noção    | Pessoa que utiliza o aplicativo |
| Impacto  | Realiza as ações no aplicativo, não é necessário cadastro e [login](https://requisitos-de-software.github.io/2022.2-FifaPlus/Modelagem/Léxicos/#login) para algumas funcionalidades |

<div id="login"></div>

### 3.3 - Logar
| Elemento | Descrição |
| :------: | :-------- |
| Nome     |  Logar |
| Classificação | Verbo |
| Sinônimos| Entrar, Acessar, Logar |
| Noção    | Libera acesso a algumas funcionalidades do aplicativo|
| Impacto  | O [usuário](https://requisitos-de-software.github.io/2022.2-FifaPlus/Modelagem/Léxicos/#usuarios) podem efetuar o login caso queira utilizar algumas das funcionalidades específicas que necessitam de tal. |

<div id="logado"></div>

### 3.4 - Logado
| Elemento | Descrição |
| :------: | :-------- |
| Nome     |  Logado |
| Classificação | Estado |
| Sinônimos| Conectado, Autenticado |
| Noção    | Um [usuário](https://requisitos-de-software.github.io/2022.2-FifaPlus/Modelagem/Léxicos/#usuarios) que se autentica com os dados de sua conta |
| Impacto  | Um [usuário](https://requisitos-de-software.github.io/2022.2-FifaPlus/Modelagem/Léxicos/#usuarios) logado pode utilizar de ferramentas e funcionalidades mais sofisticadas no app, como escolher sua [seleção](https://requisitos-de-software.github.io/2022.2-FifaPlus/Modelagem/Léxicos/#selecoes) favorita e participar do bolão. |

<div id="deslogado"></div>

### 3.5 - Deslogar
| Elemento | Descrição |
| :------: | :-------- |
| Nome     |  Deslogar |
| Classificação | Estado |
| Sinônimos| Desconectado |
| Noção    | Um [usuário](https://requisitos-de-software.github.io/2022.2-FifaPlus/Modelagem/Léxicos/#usuarios) que não se autentica com os dados de sua conta |
| Impacto  | Um [usuário](https://requisitos-de-software.github.io/2022.2-FifaPlus/Modelagem/Léxicos/#usuarios) deslogado tem acesso restritor e limitado as funcionalidades dos sistemas. |

<div id="videos"></div>

### 3.6 - Videos
| Elemento | Descrição |
| :------: | :-------- |
| Nome     | Videos |
| Classificação | Objeto |
| Sinônimos| Gravação, Cortes, Melhores Momentos |
| Noção    | São fragmentos importantes tirados de transmissões de partida da copa. |
| Impacto  | Podem ser assistidos, [compartilhados](https://requisitos-de-software.github.io/2022.2-FifaPlus/Modelagem/Léxicos/#compartilhar) e pausados|


<div id="interface"></div>

### 3.7 - Interface
| Elemento | Descrição |
| :------: | :-------- |
| Nome     | Interface |
| Classificação | Objeto |
| Sinônimos| Pagina, Tela |
| Noção    | Uma interface pode interagir e ser interagida|
| Impacto  | A interface são os elementos que aparecem na tela e como estão distribuídos, contendo o menu de [melhores momentos](https://requisitos-de-software.github.io/2022.2-FifaPlus/Modelagem/Léxicos/#melhores-momentos), [equipe](https://requisitos-de-software.github.io/2022.2-FifaPlus/Modelagem/Léxicos/#equipe) e [resultados](https://requisitos-de-software.github.io/2022.2-FifaPlus/Modelagem/Léxicos/#resultados) |


<div id="equipes"></div>

### 3.8 - Aba De Equipes
| Elemento | Descrição |
| :------: | :-------- |
| Nome     | Equipes |
| Classificação | Objeto |
| Sinônimos| Aba de Times, Aba de Seleções, Aba de Países |
| Noção    | A aba de equipes é onde se localiza as [seleções](https://requisitos-de-software.github.io/2022.2-FifaPlus/Modelagem/Léxicos/#selecoes) que estão participando da copa do mundo de 2022. |
| Impacto  | Os [usuários](https://requisitos-de-software.github.io/2022.2-FifaPlus/Modelagem/Léxicos/#usuarios) podem clicar em uma [seleção](https://requisitos-de-software.github.io/2022.2-FifaPlus/Modelagem/Léxicos/#selecoes) obtendo informações das mesmas. |


<div id="selecoes"></div>

### 3.9 - Seleções
| Elemento | Descrição |
| :------: | :-------- |
| Nome     | Pausado |
| Classificação | Objeto |
| Sinônimos| Times, Países, Equipes |
| Noção    | São as [equipes](https://requisitos-de-software.github.io/2022.2-FifaPlus/Modelagem/Léxicos/#equipes) que estão participando dos [jogos](https://requisitos-de-software.github.io/2022.2-FifaPlus/Modelagem/Léxicos/#jogo) da copa do mundo de 2022, podem ser encontradas nas [aba de equipes](https://requisitos-de-software.github.io/2022.2-FifaPlus/Modelagem/Léxicos/#equipes). |
| Impacto  | Os [usuários](https://requisitos-de-software.github.io/2022.2-FifaPlus/Modelagem/Léxicos/#usuarios) podem clicar em uma seleção obtendo informações como [calendário](https://requisitos-de-software.github.io/2022.2-FifaPlus/Modelagem/Léxicos/#calendario) de jogos, [estatísticas](https://requisitos-de-software.github.io/2022.2-FifaPlus/Modelagem/Léxicos/#estatisticas), [elenco](https://requisitos-de-software.github.io/2022.2-FifaPlus/Modelagem/Léxicos/#elenco) e [notícias](https://requisitos-de-software.github.io/2022.2-FifaPlus/Modelagem/Léxicos/#noticias) relacionadas.|


<div id="calendario"></div>

### 3.10 - Calendário
| Elemento | Descrição |
| :------: | :-------- |
| Nome     | Calendário |
| Classificação | Objeto |
| Sinônimos| Publicado, Cronograma, Histórico de jogos |
| Noção    | O calendário é onde o [usuário](https://requisitos-de-software.github.io/2022.2-FifaPlus/Modelagem/Léxicos/#usuarios) pode verificar o [resultado](https://requisitos-de-software.github.io/2022.2-FifaPlus/Modelagem/Léxicos/#resultados) dos [jogos](https://requisitos-de-software.github.io/2022.2-FifaPlus/Modelagem/Léxicos/#jogo) passados e a data e hora dos [jogos](https://requisitos-de-software.github.io/2022.2-FifaPlus/Modelagem/Léxicos/#jogo) que estão por vir. |
| Impacto  | Os [usuários](https://requisitos-de-software.github.io/2022.2-FifaPlus/Modelagem/Léxicos/#usuarios) podem clicar em cada jogo e verificar [notícias](https://requisitos-de-software.github.io/2022.2-FifaPlus/Modelagem/Léxicos/#noticias) e o resumo do jogo.  |

<div id="noticias"></div>

### 3.11 - Notícias
| Elemento | Descrição |
| :------: | :-------- |
| Nome     | Notícias |
| Classificação | Objeto |
| Sinônimos| Descrição, Resumo, Informação |
| Noção    | São informações relacionadas a uma [seleção](https://requisitos-de-software.github.io/2022.2-FifaPlus/Modelagem/Léxicos/#selecoes), jogador, [jogo](https://requisitos-de-software.github.io/2022.2-FifaPlus/Modelagem/Léxicos/#jogo) ou a copa no geral. |
| Impacto  | Os [usuário](https://requisitos-de-software.github.io/2022.2-FifaPlus/Modelagem/Léxicos/#usuarios) podem clicar em uma noticia ler e [compartilhar](https://requisitos-de-software.github.io/2022.2-FifaPlus/Modelagem/Léxicos/#compartilhar) . |

<div id="elenco"></div>

### 3.12 - Elenco
| Elemento | Descrição |
| :------: | :-------- |
| Nome     | Elenco |
| Classificação | Objeto |
| Sinônimos| Time, Conjunto, Formação |
| Noção    | São jogadores que compõem as [seleções](https://requisitos-de-software.github.io/2022.2-FifaPlus/Modelagem/Léxicos/#selecoes). |
| Impacto  | Os [usuário](https://requisitos-de-software.github.io/2022.2-FifaPlus/Modelagem/Léxicos/#usuarios) podem clicar em elenco e [visualizar](https://requisitos-de-software.github.io/2022.2-FifaPlus/Modelagem/Léxicos/#visualizar) os jogadores que compõem o elenco. |

<div id="estatisticas"></div>

### 3.13 - Estatísticas  
| Elemento | Descrição |
| :------: | :-------- |
| Nome     | Elenco |
| Classificação | Objeto |
| Sinônimos| Dados, Resultados |
| Noção    | São dados coletados durante os [jogos](https://requisitos-de-software.github.io/2022.2-FifaPlus/Modelagem/Léxicos/#jogos) como gols, passes, cartões, etc... |
| Impacto  | Os [usuário](https://requisitos-de-software.github.io/2022.2-FifaPlus/Modelagem/Léxicos/#usuarios) podem clicar em Estatísticas e [visualizar](https://requisitos-de-software.github.io/2022.2-FifaPlus/Modelagem/Léxicos/#visualizar) os dados.  |

<div id="compartilhar"></div>

### 3.14 - Compartilhar  
| Elemento | Descrição |
| :------: | :-------- |
| Nome     | Compartilhar |
| Classificação | Verbo |
| Sinônimos| Distribuir, Partilhar, Passar para frente |
| Noção    | É o ato de um [usuário](https://requisitos-de-software.github.io/2022.2-FifaPlus/Modelagem/Léxicos/#usuarios) copiar o link de um [video](https://requisitos-de-software.github.io/2022.2-FifaPlus/Modelagem/Léxicos/#videos) ou postá-lo em outra rede social.|
| Impacto  | Um [video](https://requisitos-de-software.github.io/2022.2-FifaPlus/Modelagem/Léxicos/#videos) pode ser [compartilhado](https://requisitos-de-software.github.io/2022.2-FifaPlus/Modelagem/Léxicos/#compartilhado) em diversas redes sociais fora do App|

<div id="visualizar"></div>

### 3.15 - Visualizar  
| Elemento | Descrição |
| :------: | :-------- |
| Nome     | Visualizar |
| Classificação | Verbo |
| Sinônimos| Assistir, Ver |
| Noção    | É o ato de assistir a um [video](https://requisitos-de-software.github.io/2022.2-FifaPlus/Modelagem/Léxicos/#videos) ou ver e ler uma [notícia](https://requisitos-de-software.github.io/2022.2-FifaPlus/Modelagem/Léxicos/#noticias)|
| Impacto  | Um [video](https://requisitos-de-software.github.io/2022.2-FifaPlus/Modelagem/Léxicos/#videos) pode ser visualizado e [compartilhado](https://requisitos-de-software.github.io/2022.2-FifaPlus/Modelagem/Léxicos/#compartilhar)|

<div id="resultados"></div>

### 3.16 - Resultados  
| Elemento | Descrição |
| :------: | :-------- |
| Nome     | Visualizar |
| Classificação | Objeto |
| Sinônimos| Termino, Conclusão |
| Noção    | Aba onde fica os [jogos](https://requisitos-de-software.github.io/2022.2-FifaPlus/Modelagem/Léxicos/#jogos) e seus placares|
| Impacto  | O [usuário](https://requisitos-de-software.github.io/2022.2-FifaPlus/Modelagem/Léxicos/#usuarios) pode clicar em um [jogo](https://requisitos-de-software.github.io/2022.2-FifaPlus/Modelagem/Léxicos/#jogos) para ter acesso a mais detalhes|

<div id="jogos"></div>

### 3.17 - Jogos  
| Elemento | Descrição |
| :------: | :-------- |
| Nome     | Jogo |
| Classificação | Objeto |
| Sinônimos| Match, Partida, rodada |
| Noção    | São as partidas que dão origem aos [videos](https://requisitos-de-software.github.io/2022.2-FifaPlus/Modelagem/Léxicos/#videos), [notícias](https://requisitos-de-software.github.io/2022.2-FifaPlus/Modelagem/Léxicos/#noticias) e [estatísticas](https://requisitos-de-software.github.io/2022.2-FifaPlus/Modelagem/Léxicos/#estatisticas) |
| Impacto  | O [usuário](https://requisitos-de-software.github.io/2022.2-FifaPlus/Modelagem/Léxicos/#usuarios) obter todo os tipos de [estatísticas](https://requisitos-de-software.github.io/2022.2-FifaPlus/Modelagem/Léxicos/#estatisticas) do jogo.|

## 4. Referências

> - Milene Serrano, Requisitos - Aula 07. Acesso em: 17 de jul. de 2022. Disponível em: Aprender3.

## 5. Histórico de Versão
| Data |   Versão    |       Descrição       |     Autor     |    Revisor    |
|:------:|:----------:|:---------------------:|:-------------:|:-------------:|
|  11/12/2022  | 1.0 | Criação do escopo do documento  |     Thiago Cerqueira     | Eric Chagas |
|  12/12/2022  | 1.1 | Adição dos links internos  |     Thiago Cerqueira     | Eric Chagas |
|  12/12/2022  | 1.2 | Correção ortográfica  |     Thiago Cerqueira     | Eric Chagas |
|  12/12/2022  | 1.3 | Correção de links internos  |     Thiago Cerqueira     | Eric Chagas |
