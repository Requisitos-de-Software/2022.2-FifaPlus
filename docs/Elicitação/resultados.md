# Resultados da Elicitação

## 1. Introdução

Esse documento apresenta os resultados da elicitação de requisitos realizada pela equipe, e tem como objetivo demonstrar todos os requisitos elicitados por meio das quatro técnicas de elicitação utilizadas. 

## 2. Processo de elicitação

Durante o processo de elicitação dos requisitos do Fifa Plus, foram empregadas as técnicas [Brainstorm](https://requisitos-de-software.github.io/2022.2-FifaPlus/Elicita%C3%A7%C3%A3o/T%C3%A9cnicas/brainstorming/)[¹](#ancora1), [Introspecção](https://requisitos-de-software.github.io/2022.2-FifaPlus/Elicita%C3%A7%C3%A3o/T%C3%A9cnicas/introspeccao/), [Observação](https://requisitos-de-software.github.io/2022.2-FifaPlus/Elicita%C3%A7%C3%A3o/T%C3%A9cnicas/observacao/)[²](#ancora2) e [Storytelling](https://requisitos-de-software.github.io/2022.2-FifaPlus/Elicita%C3%A7%C3%A3o/T%C3%A9cnicas/storytelling/)[³](#ancora3) . Nesse sentido, foram elicitados um total de 49 requisitos, dentre os quais foram identificados pelo time 26 requisitos funcionais e 23 requisitos não funcionais. 

### 2.1. Listagem dos requisitos

A listagem dos requisitos segue o seguinte padrão de identificação e rastreabilidade: 

- **ID do requisito**: É o código identificador do requisito que deixa explicito o método que o gerou, e que pode ser consultado na página do método em questão.
    - Modelo do ID do requisito: Um código de até 4 caractéres em que os caractéres inciais (letras) representam o método utilizado para elicita-lo, onde **B** remete ao Brainstorm[¹](#ancora1), **OB** remete à Observação[²](#ancora2) e **ST** remete ao Storytelling[³](#ancora3).
    - Exemplo: **OB01**. Requisito número 01 elicitado pelo método Observação[²](#ancora2).
- **Descrição**: Descrição do Requisito
- **Tipo**: Requisito funcional ou não funcional, onde **RF** representa requisito funcional e **RNF** representa requisito não funcional.

Esse padrão foi utilizado para que seja fornecida uma visão ampla e descritiva acerca do método utilizado para elicitar determinado requisito, sua descrição e sua condição de reqisito funcional ou não funcional.

#### 2.1.1 Requisitos Funcionais

Na (Tabela 1) podem ser visualizados todos os requisitos funcionais elicitados.

|  ID  |                                                 Descrição                                                 | Tipo |
| :--: | :-------------------------------------------------------------------------------------------------------: | :--: |
| B03  |                 O usuário deve ser capaz de compartilhar os melhores momentos da partida                  |  RF  |
| B04  |                    O usuário deve ser capaz de avaliar os melhores momentos da partida                    |  RF  |
| B05  |        O usuário deve ser capaz de compartilhar o video de melhores momentos da partida na sua TV         |  RF  |
| B19  | O usuário deve ser capaz de visualizar o horário de jogo de cada seleção dependendo do seu pais de origem |  RF  |
| B22  |                   O usuário deve ser capaz de escolher seleção favorita a ganhar a copa                   |  RF  |
| B23  |                   O usuário deve ser capaz de escolher seleção favorita a ganhar o jogo                   |  RF  |
| B24  |                     O usuário deve ser capaz de escolher o saldo de gols de cada jogo                     |  RF  |
| B25  |                         O usuário deve ser capaz de escolher a estrela da partida                         |  RF  |
| B26  |                      O usuário deve ser capaz acumular pontos com palpites do jogos                       |  RF  |
| B27  |                                O usuário deve ser capaz de cadastrar email                                |  RF  |
| B28  |                                O usuário deve ser capaz de cadastrar senha                                |  RF  |
| B29  |                              Deve ser possível reenviar e-mail de validação                               |  RF  |
| B30  |                                  O usuário deve ser capaz  alterar email                                  |  RF  |
| B31  |                                  O usuário deve ser capaz  alterar senha                                  |  RF  |
| B32  |                                 O usuário deve ser capaz de inserir Login                                 |  RF  |
| B33  |                               O usuário deve ser capaz de inserir uma senha                               |  RF  |
| OB01 |                               O usuário deve ser capaz de buscar pelo jogo                                |  RF  |
| OB02 |                                O usuário deve poder trocar o idioma do app                                |  RF  |
| OB03 |                               O usuário deve ser capaz de transmitir a tela                               |  RF  |
| OB04 |                            O usuário deve poder escolher a qualidade do vídeo                             |  RF  |
| OB05 |                              O usuário deve poder usar a opção de tela cheia                              |  RF  |
| OB06 |                           O usuário deve ser capaz de ver os jogadores do time                            |  RF  |
| OB07 |                          O usuário deve ser capaz de ver o calendario dos jogos                           |  RF  |
| OB08 |                       O usuário  deve ser capaz de ver onde o jogo será transmitido                       |  RF  |
| OB09 |                                  O usuário pode ver informações da conta                                  |  RF  |
| OB10 |                       O usuário pode escolher bloquear assitir via dados de celular                       |  RF  |

###### Tabela 1: Requisitos Funcionais. Fonte: Autoria própria.

#### 2.1.2 Requisitos Funcionais

Na (Tabela 1) podem ser visualizados todos os requisitos funcionais elicitados.

|  ID  |                                                        Descrição                                                        | Tipo |
| :--: | :---------------------------------------------------------------------------------------------------------------------: | :--: |
| B01  |                             O usuário deve ser capaz de acessar os melhores momentos do dia                             | RNF  |
| B02  |                           O usuário deve ser capaz de acessar os melhores momentos da partida                           | RNF  |
| B06  |                      O usuário deve ser capaz de visualizar os melhores momentos de todos os grupo                      | RNF  |
| B07  |                         O usuário deve ser capaz de visualizar a bandeira de todas as seleções                          | RNF  |
| B08  |                                O usuário deve ser capaz de visualizar todas as seleções                                 | RNF  |
| B09  |                     O usuário deve ser capaz de visualizar as noticias especificas de cada seleção                      | RNF  |
| B10  |                        O usuário deve ser capaz de visualizar o calendário de todas as seleções                         | RNF  |
| B11  |                   O usuário deve ser capaz de visualizar as estatísticas especificas de cada seleção                    | RNF  |
| B12  |                       O usuário deve ser capaz de visualizar o elenco especifico de cada seleção                        | RNF  |
| B13  |                       O usuário deve ser capaz de visualizar a quantidade de gols de cada jogador                       | RNF  |
| B14  |                      O usuário deve ser capaz de visualizar a quantidade de passes de cada jogador                      | RNF  |
| B15  |                   O usuário deve ser capaz de visualizar a quantidade de cruzamentos de cada jogador                    | RNF  |
| B16  |                          O usuário deve ser capaz de visualizar o brasão de todas as seleções                           | RNF  |
| B17  |                         O usuário deve ser capaz de visualizar a quantidade de gols de seleção                          | RNF  |
| B18  |                        O usuário deve ser capaz de visualizar o horário de jogo de cada seleção                         | RNF  |
| B20  |                             O usuário deve ser capaz de visualizar o ganhador de cada jogo                              | RNF  |
| B21  |                      O usuário deve ser capaz de visualizar os jogos futuros de todas as seleções                       | RNF  |
| B34  |                                   O usuário deve ser capaz de escolher uma nova senha                                   | RNF  |
| OB11 |                                  O sistema deve possuir uma boa conexão com o servidor                                  | RNF  |
| OB12 |                                   O sistema deve possuir uma aba de melhores momentos                                   | RNF  |
| ST01 | A pessoa física usuária do aplicativo deve conseguir obter informações e acompanhar o resultado dos jogos em tempo real | RNF  |
| ST02 |           A pessoa física usuária do aplicativo deve conseguir obter notícias sobre seus jogadores favoritos            | RNF  |
| ST03 |           A pessoa física usuária do aplicativo deve conseguir obter informações sobre o calendário de jogos            | RNF  |

###### Tabela 2: Requisitos Não Funcionais. Fonte: Autoria própria.

## 3. Conclusão

Com base na análise dos requisitos listados nesse documento, é possível identificar seis principais áreas em que os requisitos estão relacionados.

- Streaming de jogos
- Melhores momentos
- Calendários e resultados
- Apostas e previsões
- Cadastro
- Login

Essas áreas serão utilizadas para a formação das histórias de usuário e dos épicos do backlog do produto.

## 4. Referência bibliográfica

> <a id="ancora1"></a>[1] Thiago Cerqueira, Wengel Rodrigues (2022) Requisitos de Software Fifa Plus. Disponível em: <https://requisitos-de-software.github.io/2022.2-FifaPlus/Elicita%C3%A7%C3%A3o/T%C3%A9cnicas/brainstorming/>. Acesso em: 3 jan. 2023.
> 
> <a id="ancora2"></a>[2] Wengel Rodrigues (2022) Requisitos de Software Fifa Plus. Disponível em: <https://requisitos-de-software.github.io/2022.2-FifaPlus/Elicita%C3%A7%C3%A3o/T%C3%A9cnicas/observacao/>. Acesso em: 3 jan. 2023.
> 
> <a id="ancora3"></a>[3] Thiago Cerqueira (2022) Requisitos de Software Fifa Plus. Disponível em: <https://requisitos-de-software.github.io/2022.2-FifaPlus/Elicita%C3%A7%C3%A3o/T%C3%A9cnicas/storytelling/>. Acesso em: 3 jan. 2023.

## 4. Histórico de versão

|    Data    | Versão |                          Descrição                                   |  Autor(es)      | Revisor(es)      |
| :--------: | :----: | :------------------------------------------------------------------: | :-------------: | :--------------: |
| 03/11/2022 |  1.0   | Criação da página e adição do conteúdo sobre os requisitos elicitados | Eric Chagas | Charles Serafim |
